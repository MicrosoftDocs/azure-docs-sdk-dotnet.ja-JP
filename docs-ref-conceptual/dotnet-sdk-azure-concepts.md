---
title: .NET 用 Azure 管理ライブラリの使用上の概念とパターン
description: ''
ms.date: 10/19/2017
ms.openlocfilehash: 0a6ae94046680b81f1222c3c2acc6df9871bff4a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190605"
---
# <a name="azure-management-library-for-net-fluent-concepts"></a><span data-ttu-id="8a0af-102">.NET 用 Azure 管理ライブラリの fluent の概念</span><span class="sxs-lookup"><span data-stu-id="8a0af-102">Azure management library for .NET fluent concepts</span></span>

<span data-ttu-id="8a0af-103">この記事は、.NET 用 Azure 管理ライブラリで fluent インターフェイスを効果的に使用する方法を理解する上で役立ちます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-103">This article will help you understand how to effectively use the fluent interface in the Azure management libraries for .NET.</span></span>

## <a name="building-resources-using-a-fluent-interface"></a><span data-ttu-id="8a0af-104">fluent インターフェイスを使用したリソースの構築</span><span class="sxs-lookup"><span data-stu-id="8a0af-104">Building resources using a fluent interface</span></span>

<span data-ttu-id="8a0af-105">fluent インターフェイスは、リソースの適切な構成を適用するメソッド チェーンを使用してオブジェクトを作成する、特定の形式のビルダー パターンです。</span><span class="sxs-lookup"><span data-stu-id="8a0af-105">A fluent interface is a specific form of the builder pattern that creates objects through a method chain that enforces correct configuration of a resource.</span></span> <span data-ttu-id="8a0af-106">たとえば、fluent インターフェイスを使用して、エントリ ポイント Azure オブジェクトが作成されます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-106">For example, the entry-point Azure object is created using a fluent interface:</span></span>

```csharp
var azure = Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

## <a name="resource-collections"></a><span data-ttu-id="8a0af-107">リソース コレクション</span><span class="sxs-lookup"><span data-stu-id="8a0af-107">Resource collections</span></span>

<span data-ttu-id="8a0af-108">上記の `Microsoft.Azure.Management.Fluent.Azure` オブジェクトは、fluent 管理ライブラリでのすべてのリソース作成のエントリ ポイントとなります。</span><span class="sxs-lookup"><span data-stu-id="8a0af-108">The `Microsoft.Azure.Management.Fluent.Azure` object shown above is the entry point for all resource creation in the fluent management libraries.</span></span> <span data-ttu-id="8a0af-109">`Azure` オブジェクトのリソース コレクションを使用して、操作の対象となるリソースの種類を選択します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-109">Select which type of resources to work with using the resource collections in the `Azure` object.</span></span> <span data-ttu-id="8a0af-110">たとえば、SQL Database の場合は次のようになります。</span><span class="sxs-lookup"><span data-stu-id="8a0af-110">For example, for SQL Database:</span></span>

```csharp
var sql = azure.SqlServers.Define(sqlServerName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .WithAdministratorLogin(administratorLogin)
    .WithAdministratorPassword(administratorPassword)
    .Create();
```

<span data-ttu-id="8a0af-111">上記のように、API とのほとんどの fluent な "対話" では、まず、操作する必要がある Azure リソースの適切なリソース コレクションを選択します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-111">As seen above, most fluent "conversations" you have with the API start with selecting the appropriate resource collection for the Azure resources you need to work with.</span></span>  <span data-ttu-id="8a0af-112">その後、Visual Studio の Intellisense に従って対話を進めます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-112">Intellisense in Visual Studio then guides you through the conversation.</span></span> 

![fluent な対話を促進する Visual Studio の Intellisense の GIF](media/dotnet-sdk-azure-concepts/vs-fluent.gif)   

## <a name="lists-and-iterations"></a><span data-ttu-id="8a0af-114">リストとイテレーション</span><span class="sxs-lookup"><span data-stu-id="8a0af-114">Lists and iterations</span></span>

<span data-ttu-id="8a0af-115">すべてのリソース コレクションには、サブスクリプションに存在するそのリソースのすべてのインスタンスを返す `List()` メソッドがあります。</span><span class="sxs-lookup"><span data-stu-id="8a0af-115">Every resource collection has a `List()` method to return every instance of that resource in your current subscription.</span></span> <span data-ttu-id="8a0af-116">たとえば、`Azure.SqlServers.List()` は、サブスクリプション内のすべての SQL サーバーを返します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-116">For example, `Azure.SqlServers.List()` returns all SQL servers in the subscription.</span></span>

<span data-ttu-id="8a0af-117">取得するリストの範囲を特定の [Azure リソース グループ](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups)に限定するには、`ListByResourceGroup()` メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-117">Use the `ListByResourceGroup()` method to scope the returned List to a specific [Azure resource group](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups).</span></span>  

<span data-ttu-id="8a0af-118">通常の `List<T>` と同様に、返されたコレクションを反復処理します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-118">Iterate over the returned collection just as you would a normal `List<T>`:</span></span>

```csharp
var vmList = azure.VirtualMachines.List();
foreach(var vm in vmList)
{
    Console.WriteLine("VM Name: {0}", vm.Name);
}
```   

## <a name="actionable-verbs"></a><span data-ttu-id="8a0af-119">アクション可能な動詞</span><span class="sxs-lookup"><span data-stu-id="8a0af-119">Actionable verbs</span></span>

<span data-ttu-id="8a0af-120">名前に動詞が含まれたリソース コレクション メソッドは、Azure でアクションを即座に実行します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-120">Resource collection methods with verbs in their names take immediate action in Azure.</span></span> <span data-ttu-id="8a0af-121">これらのメソッドは同期的に動作するため、現在のスレッドで実行されている処理は、メソッドが完了するまでブロックされます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-121">These methods work synchronously and block execution in the current thread until they complete.</span></span> 

| <span data-ttu-id="8a0af-122">動詞</span><span class="sxs-lookup"><span data-stu-id="8a0af-122">Verb</span></span>   |  <span data-ttu-id="8a0af-123">使用例</span><span class="sxs-lookup"><span data-stu-id="8a0af-123">Sample usage</span></span> |
|--------|---------------|
| <span data-ttu-id="8a0af-124">Create</span><span class="sxs-lookup"><span data-stu-id="8a0af-124">Create</span></span> | `azure.VirtualMachines.Create(listOfVMCreatables)` |
| <span data-ttu-id="8a0af-125">適用</span><span class="sxs-lookup"><span data-stu-id="8a0af-125">Apply</span></span>  | `virtualMachineScaleSet.Update().WithCapacity(6).Apply()` |
| <span data-ttu-id="8a0af-126">削除</span><span class="sxs-lookup"><span data-stu-id="8a0af-126">Delete</span></span> | `azure.Disks.DeleteById(id)` | 
| <span data-ttu-id="8a0af-127">List</span><span class="sxs-lookup"><span data-stu-id="8a0af-127">List</span></span>   | `azure.SqlServers.List()` | 
| <span data-ttu-id="8a0af-128">取得</span><span class="sxs-lookup"><span data-stu-id="8a0af-128">Get</span></span>    | `var vm  = azure.VirtualMachines.GetByResourceGroup(group, vmName)` |

>[!NOTE]
> <span data-ttu-id="8a0af-129">`Define()` と `Update()` は動詞ですが、その後に `Create()` または `Apply()` が続かない限り、他の処理がブロックされることはありません。</span><span class="sxs-lookup"><span data-stu-id="8a0af-129">`Define()` and `Update()` are verbs but do not block unless followed by a `Create()` or `Apply()`.</span></span>
 
<span data-ttu-id="8a0af-130">特定のリソース オブジェクトには、Azure のリソースの状態を変更する動詞があります。</span><span class="sxs-lookup"><span data-stu-id="8a0af-130">Specific resource objects have verbs that change the state of the resource in Azure.</span></span> <span data-ttu-id="8a0af-131">例: </span><span class="sxs-lookup"><span data-stu-id="8a0af-131">For example:</span></span>

```csharp
var vmToRestart = azure.VirtualMachines.GetById(id);
vmToRestart.Restart();
```

<span data-ttu-id="8a0af-132">このセクションで説明するほとんどのメソッドには、非同期バージョンもあります。これは、`Async` サフィックスで示されます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-132">Most of the methods described in this section have an asynchronous version as well, denoted by the suffix `Async`.</span></span>

```csharp
Task restartTask = azure.VirtualMachines.GetById(id).RestartAsync();
```

## <a name="lazy-resource-creation"></a><span data-ttu-id="8a0af-133">リソースの遅延作成</span><span class="sxs-lookup"><span data-stu-id="8a0af-133">Lazy resource creation</span></span>

<span data-ttu-id="8a0af-134">Azure リソースを作成するときに、新しいリソースがまだ存在しない別のリソースに依存していると問題が生じます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-134">A challenge when creating Azure resources arises when a new resource depends on another resource that doesn't yet exist.</span></span> <span data-ttu-id="8a0af-135">例として、新しい仮想マシンを作成するときのパブリック IP アドレスの予約とディスクの設定があります。</span><span class="sxs-lookup"><span data-stu-id="8a0af-135">An example is reserving a public IP address and setting up a disk when creating a new virtual machine.</span></span> <span data-ttu-id="8a0af-136">開発者が求めているのは、アドレスの予約やディスクの作成を確認することではなく、これらのリソースを使用して仮想マシンを構成することです。</span><span class="sxs-lookup"><span data-stu-id="8a0af-136">You don't want to verify reserving the address or the creating the disk, you just want to configure the virtual machine with those resources.</span></span>

<span data-ttu-id="8a0af-137">コードで使用し、Azure で必要な場合にのみ作成する Azure リソースを定義するには、作成可能なオブジェクトを使用します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-137">Use creatable objects to define Azure resources for use in your code but only create them when needed in Azure.</span></span> <span data-ttu-id="8a0af-138">作成可能なオブジェクトを使用して記述されたコードは、Azure 環境でのリソースの作成を管理 API にオフロードすることで、パフォーマンスを高めます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-138">Code written with creatable objects offloads resource creation in the Azure environment to the management API, boosting performance.</span></span> 

<span data-ttu-id="8a0af-139">リソース コレクションの `Create()` 動詞を使用せずに `Define()` 動詞を使用して、作成可能なオブジェクトを生成します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-139">Generate creatable objects through the resource collections' `Define()` verb without a `Create()` verb:</span></span>

```csharp
// Init a creatable Public IP Address
var publicIpAddressCreatable = azure.PublicIPAddresses.Define("publicIPAddressName")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName);
```

<span data-ttu-id="8a0af-140">作成可能なオブジェクトによって定義された Azure リソースは、サブスクリプションにまだ存在していません。</span><span class="sxs-lookup"><span data-stu-id="8a0af-140">The Azure resource defined by the creatable object does not yet exist in your subscription.</span></span> <span data-ttu-id="8a0af-141">作成可能なオブジェクトとは、管理 API が必要に応じて (`.Create()` が呼び出されたときに) 作成するリソースのローカル表現です。</span><span class="sxs-lookup"><span data-stu-id="8a0af-141">A creatable object is a local representation of a resource that the management API will create when it's needed (when `.Create()` is called).</span></span> <span data-ttu-id="8a0af-142">この作成可能なオブジェクトを、このリソースを必要とする他の Azure リソースの定義で使用します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-142">Use this creatable object in the definition of other Azure resources that need this resource.</span></span> 

```csharp
// Init a creatable VM using the creatable Public IP Address
var vmCreatable = azure.VirtualMachines.Define("creatableVM")
    // ...
    .withNewPrimaryPublicIPAddress(publicIPAddressCreatable)
    // ...
```

<span data-ttu-id="8a0af-143">リソース コレクションの `Create()` メソッドを使用して、Azure サブスクリプションにリソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-143">Create the resources in your Azure subscription using the `Create()` method for the resource collection.</span></span> 

```csharp
// Create the VM and its Public IP Address
var virtualMachine = azure.VirtualMachines.Create(vmCreatable);
```

<span data-ttu-id="8a0af-144">`Create()` に作成可能なオブジェクトを渡すと、単一のリソース オブジェクトではなく、`ICreatedResources` オブジェクトが返されます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-144">Passing creatable objects to `Create()` returns a `ICreatedResources` object instead of a single resource object.</span></span>  <span data-ttu-id="8a0af-145">`CreatedRelatedResource` オブジェクトを使用すると、リソース コレクションの特定の種類のリソースだけでなく、`Create()` の呼び出しによって作成されたすべてのリソースにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-145">The `CreatedRelatedResource` object lets you access all resources created by the `Create()` call, not just the type from the resource collection.</span></span> <span data-ttu-id="8a0af-146">前の例で作成した仮想マシンの、Azure で作成されたパブリック IP アドレスにアクセスするには、次のコードを使用します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-146">To access the public IP address created in Azure for the virtual machine created in the above example:</span></span>

```csharp
var pip = virtualMachine.CreatedRelatedResource(publicIPAddressCreatable.Key()) as PublicIPAddress;;
```    

## <a name="exception-handling"></a><span data-ttu-id="8a0af-147">例外処理</span><span class="sxs-lookup"><span data-stu-id="8a0af-147">Exception handling</span></span>

<span data-ttu-id="8a0af-148">管理 API では、`Microsoft.Rest.RestException` を拡張する例外クラスを定義します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-148">The management API defines exception classes that extend `Microsoft.Rest.RestException`.</span></span> <span data-ttu-id="8a0af-149">管理 API によって生成された例外は、対応する `try` ステートメントの後の `catch (RestException exception)` ブロックでキャッチします。</span><span class="sxs-lookup"><span data-stu-id="8a0af-149">Catch exceptions generated by management API, with a `catch (RestException exception)` block after the relevant `try` statement.</span></span>

## <a name="logs-and-tracing"></a><span data-ttu-id="8a0af-150">ログとトレース</span><span class="sxs-lookup"><span data-stu-id="8a0af-150">Logs and tracing</span></span>

<span data-ttu-id="8a0af-151">.NET 用 fluent Azure 管理ライブラリのログでは、基になる [AutoRest](https://github.com/Azure/AutoRest) のサービス クライアント トレースを活用します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-151">Logging in the fluent Azure management libraries for .NET leverages the underlying [AutoRest](https://github.com/Azure/AutoRest) service client tracing.</span></span>

<span data-ttu-id="8a0af-152">`Microsoft.Rest.IServiceClientTracingInterceptor` を実装するクラスを作成します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-152">Create a class that implements `Microsoft.Rest.IServiceClientTracingInterceptor`.</span></span>  <span data-ttu-id="8a0af-153">このクラスは、ログ メッセージをインターセプトし、現在使用している任意のログ メカニズムに渡す役割を担います。</span><span class="sxs-lookup"><span data-stu-id="8a0af-153">This class will be responsible for intercepting log messages and passing them to whatever logging mechanism you're using.</span></span>  <span data-ttu-id="8a0af-154">この例では、メッセージをコンソールに書き込むだけですが、Log4Net、`Microsoft.Extensions.Logging`、またはその他のログ記録フレームワークにメッセージを渡すこともできます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-154">In this example, we're just writing messages to the console, but you could also pass them to Log4Net, `Microsoft.Extensions.Logging`, or any other logging framework.</span></span>

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

<span data-ttu-id="8a0af-155">`Microsoft.Azure.Management.Fluent.Azure` オブジェクトを作成する前に、`ServiceClientTracing.AddTracingInterceptor()` を呼び出して上記で作成した `IServiceClientTracingInterceptor` を初期化し、`ServiceClientTracing.IsEnabled` を *true* に設定します。</span><span class="sxs-lookup"><span data-stu-id="8a0af-155">Before creating the `Microsoft.Azure.Management.Fluent.Azure` object, initialize the `IServiceClientTracingInterceptor` you created above by calling `ServiceClientTracing.AddTracingInterceptor()` and set `ServiceClientTracing.IsEnabled` to *true*.</span></span>  <span data-ttu-id="8a0af-156">`Azure` オブジェクトを作成するときに、クライアントを AutoRest のサービス クライアント トレースに接続するための `.WithDelegatingHandler()` メソッドと `.WithLogLevel()` メソッドを含めます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-156">When you create the `Azure` object, include the `.WithDelegatingHandler()` and `.WithLogLevel()` methods to wire up the client to AutoRest's service client tracing.</span></span>

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

<span data-ttu-id="8a0af-157">`HttpLoggingDelegatingHandler` のログ レベルの定義は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="8a0af-157">The `HttpLoggingDelegatingHandler` log levels are defined as follows:</span></span>

| <span data-ttu-id="8a0af-158">トレース レベル</span><span class="sxs-lookup"><span data-stu-id="8a0af-158">Trace level</span></span> | <span data-ttu-id="8a0af-159">有効になるログ</span><span class="sxs-lookup"><span data-stu-id="8a0af-159">Logging enabled</span></span> 
| ------------ | ---------------
| <span data-ttu-id="8a0af-160">HttpLoggingDelegatingHandler.Level.None</span><span class="sxs-lookup"><span data-stu-id="8a0af-160">HttpLoggingDelegatingHandler.Level.None</span></span> | <span data-ttu-id="8a0af-161">出力なし</span><span class="sxs-lookup"><span data-stu-id="8a0af-161">No output</span></span>
| <span data-ttu-id="8a0af-162">HttpLoggingDelegatingHandler.Level.Basic</span><span class="sxs-lookup"><span data-stu-id="8a0af-162">HttpLoggingDelegatingHandler.Level.Basic</span></span> | <span data-ttu-id="8a0af-163">基になる REST 呼び出しの URL、応答コード、時間がログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-163">Logs the URLs to underlying REST calls, response codes and times</span></span>
| <span data-ttu-id="8a0af-164">HttpLoggingDelegatingHandler.Level.Body</span><span class="sxs-lookup"><span data-stu-id="8a0af-164">HttpLoggingDelegatingHandler.Level.Body</span></span> | <span data-ttu-id="8a0af-165">Basic の全出力内容に加えて、REST 呼び出しの要求と応答の本文がログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-165">Everything in Basic plus request and response bodies for the REST calls</span></span>
| <span data-ttu-id="8a0af-166">HttpLoggingDelegatingHandler.Level.Headers</span><span class="sxs-lookup"><span data-stu-id="8a0af-166">HttpLoggingDelegatingHandler.Level.Headers</span></span> | <span data-ttu-id="8a0af-167">Basic の全出力内容に加えて、REST 呼び出しの要求ヘッダーと応答ヘッダーがログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-167">Everything in Basic plus the request and response headers REST calls</span></span>
| <span data-ttu-id="8a0af-168">HttpLoggingDelegatingHandler.Level.BodyAndHeaders</span><span class="sxs-lookup"><span data-stu-id="8a0af-168">HttpLoggingDelegatingHandler.Level.BodyAndHeaders</span></span> | <span data-ttu-id="8a0af-169">Body と Headers の両方のログ レベルの全出力内容がログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="8a0af-169">Everything in both Body and Headers log level</span></span>
