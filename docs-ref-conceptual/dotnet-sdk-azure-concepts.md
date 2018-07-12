---
title: .NET 用 Azure 管理ライブラリの使用上の概念とパターン
description: ''
keywords: Azure, .NET, SDK, API, パターン, 概念, fluent, ログ
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: b817216e114e5ab3ff22c1c5adb0f892c7874147
ms.sourcegitcommit: 1c2e1fd031ad012d6888fcde3cd325f7e8e49e0f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2018
ms.locfileid: "29752864"
---
# <a name="azure-management-library-for-net-fluent-concepts"></a>.NET 用 Azure 管理ライブラリの fluent の概念

この記事は、.NET 用 Azure 管理ライブラリで fluent インターフェイスを効果的に使用する方法を理解する上で役立ちます。

## <a name="building-resources-using-a-fluent-interface"></a>fluent インターフェイスを使用したリソースの構築

fluent インターフェイスは、リソースの適切な構成を適用するメソッド チェーンを使用してオブジェクトを作成する、特定の形式のビルダー パターンです。 たとえば、fluent インターフェイスを使用して、エントリ ポイント Azure オブジェクトが作成されます。

```csharp
var azure = Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

## <a name="resource-collections"></a>リソース コレクション

上記の `Microsoft.Azure.Management.Fluent.Azure` オブジェクトは、fluent 管理ライブラリでのすべてのリソース作成のエントリ ポイントとなります。 `Azure` オブジェクトのリソース コレクションを使用して、操作の対象となるリソースの種類を選択します。 たとえば、SQL Database の場合は次のようになります。

```csharp
var sql = azure.SqlServers.Define(sqlServerName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .WithAdministratorLogin(administratorLogin)
    .WithAdministratorPassword(administratorPassword)
    .Create();
```

上記のように、API とのほとんどの fluent な "対話" では、まず、操作する必要がある Azure リソースの適切なリソース コレクションを選択します。  その後、Visual Studio の Intellisense に従って対話を進めます。 

![fluent な対話を促進する Visual Studio の Intellisense の GIF](media/dotnet-sdk-azure-concepts/vs-fluent.gif)   

## <a name="lists-and-iterations"></a>リストとイテレーション

すべてのリソース コレクションには、サブスクリプションに存在するそのリソースのすべてのインスタンスを返す `List()` メソッドがあります。 たとえば、`Azure.SqlServers.List()` は、サブスクリプション内のすべての SQL サーバーを返します。

取得するリストの範囲を特定の [Azure リソース グループ](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups)に限定するには、`ListByResourceGroup()` メソッドを使用します。  

通常の `List<T>` と同様に、返されたコレクションを反復処理します。

```csharp
var vmList = azure.VirtualMachines.List();
foreach(var vm in vmList)
{
    Console.WriteLine("VM Name: {0}", vm.Name);
}
```   

## <a name="actionable-verbs"></a>アクション可能な動詞

名前に動詞が含まれたリソース コレクション メソッドは、Azure でアクションを即座に実行します。 これらのメソッドは同期的に動作するため、現在のスレッドで実行されている処理は、メソッドが完了するまでブロックされます。 

| 動詞   |  使用例 |
|--------|---------------|
| Create | `azure.VirtualMachines.Create(listOfVMCreatables)` |
| 適用  | `virtualMachineScaleSet.Update().WithCapacity(6).Apply()` |
| Delete | `azure.Disks.DeleteById(id)` | 
| List   | `azure.SqlServers.List()` | 
| 取得    | `var vm  = azure.VirtualMachines.GetByResourceGroup(group, vmName)` |

>[!NOTE]
> `Define()` と `Update()` は動詞ですが、その後に `Create()` または `Apply()` が続かない限り、他の処理がブロックされることはありません。
 
特定のリソース オブジェクトには、Azure のリソースの状態を変更する動詞があります。 例: 

```csharp
var vmToRestart = azure.VirtualMachines.GetById(id);
vmToRestart.Restart();
```

このセクションで説明するほとんどのメソッドには、非同期バージョンもあります。これは、`Async` サフィックスで示されます。

```csharp
Task restartTask = azure.VirtualMachines.GetById(id).RestartAsync();
```

## <a name="lazy-resource-creation"></a>リソースの遅延作成

Azure リソースを作成するときに、新しいリソースがまだ存在しない別のリソースに依存していると問題が生じます。 例として、新しい仮想マシンを作成するときのパブリック IP アドレスの予約とディスクの設定があります。 開発者が求めているのは、アドレスの予約やディスクの作成を確認することではなく、これらのリソースを使用して仮想マシンを構成することです。

コードで使用し、Azure で必要な場合にのみ作成する Azure リソースを定義するには、作成可能なオブジェクトを使用します。 作成可能なオブジェクトを使用して記述されたコードは、Azure 環境でのリソースの作成を管理 API にオフロードすることで、パフォーマンスを高めます。 

リソース コレクションの `Create()` 動詞を使用せずに `Define()` 動詞を使用して、作成可能なオブジェクトを生成します。

```csharp
// Init a creatable Public IP Address
var publicIpAddressCreatable = azure.PublicIPAddresses.Define("publicIPAddressName")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName);
```

作成可能なオブジェクトによって定義された Azure リソースは、サブスクリプションにまだ存在していません。 作成可能なオブジェクトとは、管理 API が必要に応じて (`.Create()` が呼び出されたときに) 作成するリソースのローカル表現です。 この作成可能なオブジェクトを、このリソースを必要とする他の Azure リソースの定義で使用します。 

```csharp
// Init a creatable VM using the creatable Public IP Address
var vmCreatable = azure.VirtualMachines.Define("creatableVM")
    // ...
    .withNewPrimaryPublicIPAddress(publicIPAddressCreatable)
    // ...
```

リソース コレクションの `Create()` メソッドを使用して、Azure サブスクリプションにリソースを作成します。 

```csharp
// Create the VM and its Public IP Address
var virtualMachine = azure.VirtualMachines.Create(vmCreatable);
```

`Create()` に作成可能なオブジェクトを渡すと、単一のリソース オブジェクトではなく、`ICreatedResources` オブジェクトが返されます。  `CreatedRelatedResource` オブジェクトを使用すると、リソース コレクションの特定の種類のリソースだけでなく、`Create()` の呼び出しによって作成されたすべてのリソースにアクセスできます。 前の例で作成した仮想マシンの、Azure で作成されたパブリック IP アドレスにアクセスするには、次のコードを使用します。

```csharp
var pip = virtualMachine.CreatedRelatedResource(publicIPAddressCreatable.Key()) as PublicIPAddress;;
```    

## <a name="exception-handling"></a>例外処理

管理 API では、`Microsoft.Rest.RestException` を拡張する例外クラスを定義します。 管理 API によって生成された例外は、対応する `try` ステートメントの後の `catch (RestException exception)` ブロックでキャッチします。

## <a name="logs-and-tracing"></a>ログとトレース

.NET 用 fluent Azure 管理ライブラリのログでは、基になる [AutoRest](https://github.com/Azure/AutoRest) のサービス クライアント トレースを活用します。

`Microsoft.Rest.IServiceClientTracingInterceptor` を実装するクラスを作成します。  このクラスは、ログ メッセージをインターセプトし、現在使用している任意のログ メカニズムに渡す役割を担います。  この例では、メッセージをコンソールに書き込むだけですが、Log4Net、`Microsoft.Extensions.Logging`、またはその他のログ記録フレームワークにメッセージを渡すこともできます。

```csharp
class ConsoleTracer : IServiceClientTracingInterceptor
{
    public void Information(string message)
    {
        Console.WriteLine(message);
    }

    public void TraceError(string invocationId, Exception exception)
    {
        Console.WriteLine("Exception in {0}: {1}", invocationId, exception);
    }

    public void ReceiveResponse(string invocationId, HttpResponseMessage response) { }

    public void SendRequest(string invocationId, HttpRequestMessage request) { }

    public void Configuration(string source, string name, string value) { }

    public void EnterMethod(string invocationId, object instance, string method, IDictionary<string, object> parameters) { }

    public void ExitMethod(string invocationId, object returnValue) { }
}
```

`Microsoft.Azure.Management.Fluent.Azure` オブジェクトを作成する前に、`ServiceClientTracing.AddTracingInterceptor()` を呼び出して上記で作成した `IServiceClientTracingInterceptor` を初期化し、`ServiceClientTracing.IsEnabled` を *true* に設定します。  `Azure` オブジェクトを作成するときに、クライアントを AutoRest のサービス クライアント トレースに接続するための `.WithDelegatingHandler()` メソッドと `.WithLogLevel()` メソッドを含めます。

```csharp
ServiceClientTracing.AddTracingInterceptor(new ConsoleTracer());
ServiceClientTracing.IsEnabled = true;

var azure = Azure
    .Configure()
    .WithDelegatingHandler(new HttpLoggingDelegatingHandler())
    .WithLogLevel(HttpLoggingDelegatingHandler.Level.Basic)
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

`HttpLoggingDelegatingHandler` のログ レベルの定義は次のとおりです。

| トレース レベル | 有効になるログ 
| ------------ | ---------------
| HttpLoggingDelegatingHandler.Level.None | 出力なし
| HttpLoggingDelegatingHandler.Level.Basic | 基になる REST 呼び出しの URL、応答コード、時間がログに記録されます。
| HttpLoggingDelegatingHandler.Level.Body | Basic の全出力内容に加えて、REST 呼び出しの要求と応答の本文がログに記録されます。
| HttpLoggingDelegatingHandler.Level.Headers | Basic の全出力内容に加えて、REST 呼び出しの要求ヘッダーと応答ヘッダーがログに記録されます。
| HttpLoggingDelegatingHandler.Level.BodyAndHeaders | Body と Headers の両方のログ レベルの全出力内容がログに記録されます。
