---
title: ".NET 用 Azure 管理ライブラリの使用上の概念とパターン"
description: 
keywords: "Azure, .NET, SDK, API, パターン, 概念, fluent, ログ"
author: camsoper
ms.author: casoper
manager: douge
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.assetid: 
ms.openlocfilehash: b2e6849f06c36de18471e55c468e984f4205f646
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-management-library-for-net-fluent-concepts"></a><span data-ttu-id="4d855-103">.NET 用 Azure 管理ライブラリの fluent の概念</span><span class="sxs-lookup"><span data-stu-id="4d855-103">Azure management library for .NET fluent concepts</span></span>

<span data-ttu-id="4d855-104">この記事は、.NET 用 Azure 管理ライブラリで fluent インターフェイスを効果的に使用する方法を理解する上で役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4d855-104">This article will help you understand how to effectively use the fluent interface in the Azure management libraries for .NET.</span></span>

## <a name="building-resources-using-a-fluent-interface"></a><span data-ttu-id="4d855-105">fluent インターフェイスを使用したリソースの構築</span><span class="sxs-lookup"><span data-stu-id="4d855-105">Building resources using a fluent interface</span></span>

<span data-ttu-id="4d855-106">fluent インターフェイスは、リソースの適切な構成を適用するメソッド チェーンを使用してオブジェクトを作成する、特定の形式のビルダー パターンです。</span><span class="sxs-lookup"><span data-stu-id="4d855-106">A fluent interface is a specific form of the builder pattern that creates objects through a method chain that enforces correct configuration of a resource.</span></span> <span data-ttu-id="4d855-107">たとえば、fluent インターフェイスを使用して、エントリ ポイント Azure オブジェクトが作成されます。</span><span class="sxs-lookup"><span data-stu-id="4d855-107">For example, the entry-point Azure object is created using a fluent interface:</span></span>

```csharp
var azure = Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

## <a name="resource-collections"></a><span data-ttu-id="4d855-108">リソース コレクション</span><span class="sxs-lookup"><span data-stu-id="4d855-108">Resource collections</span></span>

<span data-ttu-id="4d855-109">上記の `Microsoft.Azure.Management.Fluent.Azure` オブジェクトは、fluent 管理ライブラリでのすべてのリソース作成のエントリ ポイントとなります。</span><span class="sxs-lookup"><span data-stu-id="4d855-109">The `Microsoft.Azure.Management.Fluent.Azure` object shown above is the entry point for all resource creation in the fluent management libraries.</span></span> <span data-ttu-id="4d855-110">`Azure` オブジェクトのリソース コレクションを使用して、操作の対象となるリソースの種類を選択します。</span><span class="sxs-lookup"><span data-stu-id="4d855-110">Select which type of resources to work with using the resource collections in the `Azure` object.</span></span> <span data-ttu-id="4d855-111">たとえば、SQL Database の場合は次のようになります。</span><span class="sxs-lookup"><span data-stu-id="4d855-111">For example, for SQL Database:</span></span>

```csharp
var sql = azure.SqlServers.Define(sqlServerName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .WithAdministratorLogin(administratorLogin)
    .WithAdministratorPassword(administratorPassword)
    .Create();
```

<span data-ttu-id="4d855-112">上記のように、API とのほとんどの fluent な "対話" では、まず、操作する必要がある Azure リソースの適切なリソース コレクションを選択します。</span><span class="sxs-lookup"><span data-stu-id="4d855-112">As seen above, most fluent "conversations" you have with the API start with selecting the appropriate resource collection for the Azure resources you need to work with.</span></span>  <span data-ttu-id="4d855-113">その後、Visual Studio の Intellisense に従って対話を進めます。</span><span class="sxs-lookup"><span data-stu-id="4d855-113">Intellisense in Visual Studio then guides you through the conversation.</span></span> 

![fluent な対話を促進する Visual Studio の Intellisense の GIF](media/dotnet-sdk-azure-concepts/vs-fluent.gif)   

## <a name="lists-and-iterations"></a><span data-ttu-id="4d855-115">リストとイテレーション</span><span class="sxs-lookup"><span data-stu-id="4d855-115">Lists and iterations</span></span>

<span data-ttu-id="4d855-116">すべてのリソース コレクションには、サブスクリプションに存在するそのリソースのすべてのインスタンスを返す `List()` メソッドがあります。</span><span class="sxs-lookup"><span data-stu-id="4d855-116">Every resource collection has a `List()` method to return every instance of that resource in your current subscription.</span></span> <span data-ttu-id="4d855-117">たとえば、`Azure.SqlServers.List()` は、サブスクリプション内のすべての SQL サーバーを返します。</span><span class="sxs-lookup"><span data-stu-id="4d855-117">For example, `Azure.SqlServers.List()` returns all SQL servers in the subscription.</span></span>

<span data-ttu-id="4d855-118">取得するリストの範囲を特定の [Azure リソース グループ](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups)に限定するには、`ListByResourceGroup()` メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="4d855-118">Use the `ListByResourceGroup()` method to scope the returned List to a specific [Azure resource group](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups).</span></span>  

<span data-ttu-id="4d855-119">通常の `List<T>` と同様に、返されたコレクションを反復処理します。</span><span class="sxs-lookup"><span data-stu-id="4d855-119">Iterate over the returned collection just as you would a normal `List<T>`:</span></span>

```csharp
var vmList = azure.VirtualMachines.List();
foreach(var vm in vmList)
{
    Console.WriteLine("VM Name: {0}", vm.Name);
}
```   

## <a name="actionable-verbs"></a><span data-ttu-id="4d855-120">アクション可能な動詞</span><span class="sxs-lookup"><span data-stu-id="4d855-120">Actionable verbs</span></span>

<span data-ttu-id="4d855-121">名前に動詞が含まれたリソース コレクション メソッドは、Azure でアクションを即座に実行します。</span><span class="sxs-lookup"><span data-stu-id="4d855-121">Resource collection methods with verbs in their names take immediate action in Azure.</span></span> <span data-ttu-id="4d855-122">これらのメソッドは同期的に動作するため、現在のスレッドで実行されている処理は、メソッドが完了するまでブロックされます。</span><span class="sxs-lookup"><span data-stu-id="4d855-122">These methods work synchronously and block execution in the current thread until they complete.</span></span> 

| <span data-ttu-id="4d855-123">動詞</span><span class="sxs-lookup"><span data-stu-id="4d855-123">Verb</span></span>   |  <span data-ttu-id="4d855-124">使用例</span><span class="sxs-lookup"><span data-stu-id="4d855-124">Sample usage</span></span> |
|--------|---------------|
| <span data-ttu-id="4d855-125">作成</span><span class="sxs-lookup"><span data-stu-id="4d855-125">Create</span></span> | `azure.VirtualMachines.Create(listOfVMCreatables)` |
| <span data-ttu-id="4d855-126">適用</span><span class="sxs-lookup"><span data-stu-id="4d855-126">Apply</span></span>  | `virtualMachineScaleSet.Update().WithCapacity(6).Apply()` |
| <span data-ttu-id="4d855-127">削除</span><span class="sxs-lookup"><span data-stu-id="4d855-127">Delete</span></span> | `azure.Disks.DeleteById(id)` | 
| <span data-ttu-id="4d855-128">一覧表示</span><span class="sxs-lookup"><span data-stu-id="4d855-128">List</span></span>   | `azure.SqlServers.List()` | 
| <span data-ttu-id="4d855-129">取得</span><span class="sxs-lookup"><span data-stu-id="4d855-129">Get</span></span>    | `var vm  = azure.VirtualMachines.GetByResourceGroup(group, vmName)` |

>[!NOTE]
> <span data-ttu-id="4d855-130">`Define()` と `Update()` は動詞ですが、その後に `Create()` または `Apply()` が続かない限り、他の処理がブロックされることはありません。</span><span class="sxs-lookup"><span data-stu-id="4d855-130">`Define()` and `Update()` are verbs but do not block unless followed by a `Create()` or `Apply()`.</span></span>
 
<span data-ttu-id="4d855-131">特定のリソース オブジェクトには、Azure のリソースの状態を変更する動詞があります。</span><span class="sxs-lookup"><span data-stu-id="4d855-131">Specific resource objects have verbs that change the state of the resource in Azure.</span></span> <span data-ttu-id="4d855-132">For example:</span><span class="sxs-lookup"><span data-stu-id="4d855-132">For example:</span></span>

```csharp
var vmToRestart = azure.VirtualMachines.GetById(id);
vmToRestart.Restart();
```

<span data-ttu-id="4d855-133">このセクションで説明するほとんどのメソッドには、非同期バージョンもあります。これは、`Async` サフィックスで示されます。</span><span class="sxs-lookup"><span data-stu-id="4d855-133">Most of the methods described in this section have an asynchronous version as well, denoted by the suffix `Async`.</span></span>

```csharp
Task restartTask = azure.VirtualMachines.GetById(id).RestartAsync();
```

## <a name="lazy-resource-creation"></a><span data-ttu-id="4d855-134">リソースの遅延作成</span><span class="sxs-lookup"><span data-stu-id="4d855-134">Lazy resource creation</span></span>

<span data-ttu-id="4d855-135">Azure リソースを作成するときに、新しいリソースがまだ存在しない別のリソースに依存していると問題が生じます。</span><span class="sxs-lookup"><span data-stu-id="4d855-135">A challenge when creating Azure resources arises when a new resource depends on another resource that doesn't yet exist.</span></span> <span data-ttu-id="4d855-136">例として、新しい仮想マシンを作成するときのパブリック IP アドレスの予約とディスクの設定があります。</span><span class="sxs-lookup"><span data-stu-id="4d855-136">An example is reserving a public IP address and setting up a disk when creating a new virtual machine.</span></span> <span data-ttu-id="4d855-137">開発者が求めているのは、アドレスの予約やディスクの作成を確認することではなく、これらのリソースを使用して仮想マシンを構成することです。</span><span class="sxs-lookup"><span data-stu-id="4d855-137">You don't want to verify reserving the address or the creating the disk, you just want to configure the virtual machine with those resources.</span></span>

<span data-ttu-id="4d855-138">コードで使用し、Azure で必要な場合にのみ作成する Azure リソースを定義するには、作成可能なオブジェクトを使用します。</span><span class="sxs-lookup"><span data-stu-id="4d855-138">Use creatable objects to define Azure resources for use in your code but only create them when needed in Azure.</span></span> <span data-ttu-id="4d855-139">作成可能なオブジェクトを使用して記述されたコードは、Azure 環境でのリソースの作成を管理 API にオフロードすることで、パフォーマンスを高めます。</span><span class="sxs-lookup"><span data-stu-id="4d855-139">Code written with creatable objects offloads resource creation in the Azure environment to the management API, boosting performance.</span></span> 

<span data-ttu-id="4d855-140">リソース コレクションの `Create()` 動詞を使用せずに `Define()` 動詞を使用して、作成可能なオブジェクトを生成します。</span><span class="sxs-lookup"><span data-stu-id="4d855-140">Generate creatable objects through the resource collections' `Define()` verb without a `Create()` verb:</span></span>

```csharp
// Init a creatable Public IP Address
var publicIpAddressCreatable = azure.PublicIPAddresses.Define("publicIPAddressName")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName);
```

<span data-ttu-id="4d855-141">作成可能なオブジェクトによって定義された Azure リソースは、サブスクリプションにまだ存在していません。</span><span class="sxs-lookup"><span data-stu-id="4d855-141">The Azure resource defined by the creatable object does not yet exist in your subscription.</span></span> <span data-ttu-id="4d855-142">作成可能なオブジェクトとは、管理 API が必要に応じて (`.Create()` が呼び出されたときに) 作成するリソースのローカル表現です。</span><span class="sxs-lookup"><span data-stu-id="4d855-142">A creatable object is a local representation of a resource that the management API will create when it's needed (when `.Create()` is called).</span></span> <span data-ttu-id="4d855-143">この作成可能なオブジェクトを、このリソースを必要とする他の Azure リソースの定義で使用します。</span><span class="sxs-lookup"><span data-stu-id="4d855-143">Use this creatable object in the definition of other Azure resources that need this resource.</span></span> 

```csharp
// Init a creatable VM using the creatable Public IP Address
var vmCreatable = azure.VirtualMachines.Define("creatableVM")
    // ...
    .withNewPrimaryPublicIPAddress(publicIPAddressCreatable)
    // ...
```

<span data-ttu-id="4d855-144">リソース コレクションの `Create()` メソッドを使用して、Azure サブスクリプションにリソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="4d855-144">Create the resources in your Azure subscription using the `Create()` method for the resource collection.</span></span> 

```csharp
// Create the VM and its Public IP Address
var virtualMachine = azure.VirtualMachines.Create(vmCreatable);
```

<span data-ttu-id="4d855-145">`Create()` に作成可能なオブジェクトを渡すと、単一のリソース オブジェクトではなく、`ICreatedResources` オブジェクトが返されます。</span><span class="sxs-lookup"><span data-stu-id="4d855-145">Passing creatable objects to `Create()` returns a `ICreatedResources` object instead of a single resource object.</span></span>  <span data-ttu-id="4d855-146">`CreatedRelatedResource` オブジェクトを使用すると、リソース コレクションの特定の種類のリソースだけでなく、`Create()` の呼び出しによって作成されたすべてのリソースにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="4d855-146">The `CreatedRelatedResource` object lets you access all resources created by the `Create()` call, not just the type from the resource collection.</span></span> <span data-ttu-id="4d855-147">前の例で作成した仮想マシンの、Azure で作成されたパブリック IP アドレスにアクセスするには、次のコードを使用します。</span><span class="sxs-lookup"><span data-stu-id="4d855-147">To access the public IP address created in Azure for the virtual machine created in the above example:</span></span>

```csharp
var pip = virtualMachine.CreatedRelatedResource(publicIPAddressCreatable.Key()) as PublicIPAddress;;
```    

## <a name="exception-handling"></a><span data-ttu-id="4d855-148">例外処理</span><span class="sxs-lookup"><span data-stu-id="4d855-148">Exception handling</span></span>

<span data-ttu-id="4d855-149">管理 API では、`Microsoft.Rest.RestException` を拡張する例外クラスを定義します。</span><span class="sxs-lookup"><span data-stu-id="4d855-149">The management API defines exception classes that extend `Microsoft.Rest.RestException`.</span></span> <span data-ttu-id="4d855-150">管理 API によって生成された例外は、対応する `try` ステートメントの後の `catch (RestException exception)` ブロックでキャッチします。</span><span class="sxs-lookup"><span data-stu-id="4d855-150">Catch exceptions generated by management API, with a `catch (RestException exception)` block after the relevant `try` statement.</span></span>

## <a name="logs-and-tracing"></a><span data-ttu-id="4d855-151">ログとトレース</span><span class="sxs-lookup"><span data-stu-id="4d855-151">Logs and tracing</span></span>

<span data-ttu-id="4d855-152">.NET 用 fluent Azure 管理ライブラリのログでは、基になる [AutoRest](https://github.com/Azure/AutoRest) のサービス クライアント トレースを活用します。</span><span class="sxs-lookup"><span data-stu-id="4d855-152">Logging in the fluent Azure management libraries for .NET leverages the underlying [AutoRest](https://github.com/Azure/AutoRest) service client tracing.</span></span>

<span data-ttu-id="4d855-153">`Microsoft.Rest.IServiceClientTracingInterceptor` を実装するクラスを作成します。</span><span class="sxs-lookup"><span data-stu-id="4d855-153">Create a class that implements `Microsoft.Rest.IServiceClientTracingInterceptor`.</span></span>  <span data-ttu-id="4d855-154">このクラスは、ログ メッセージをインターセプトし、現在使用している任意のログ メカニズムに渡す役割を担います。</span><span class="sxs-lookup"><span data-stu-id="4d855-154">This class will be responsible for intercepting log messages and passing them to whatever logging mechanism you're using.</span></span>  <span data-ttu-id="4d855-155">この例では、メッセージをコンソールに書き込むだけですが、Log4Net、`Microsoft.Extensions.Logging`、またはその他のログ記録フレームワークにメッセージを渡すこともできます。</span><span class="sxs-lookup"><span data-stu-id="4d855-155">In this example, we're just writing messages to the console, but you could also pass them to Log4Net, `Microsoft.Extensions.Logging`, or any other logging framework.</span></span>

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

<span data-ttu-id="4d855-156">`Microsoft.Azure.Management.Fluent.Azure` オブジェクトを作成する前に、`ServiceClientTracing.AddTracingInterceptor()` を呼び出して上記で作成した `IServiceClientTracingInterceptor` を初期化し、`ServiceClientTracing.IsEnabled` を *true* に設定します。</span><span class="sxs-lookup"><span data-stu-id="4d855-156">Before creating the `Microsoft.Azure.Management.Fluent.Azure` object, initialize the `IServiceClientTracingInterceptor` you created above by calling `ServiceClientTracing.AddTracingInterceptor()` and set `ServiceClientTracing.IsEnabled` to *true*.</span></span>  <span data-ttu-id="4d855-157">`Azure` オブジェクトを作成するときに、クライアントを AutoRest のサービス クライアント トレースに接続するための `.WithDelegatingHandler()` メソッドと `.WithLogLevel()` メソッドを含めます。</span><span class="sxs-lookup"><span data-stu-id="4d855-157">When you create the `Azure` object, include the `.WithDelegatingHandler()` and `.WithLogLevel()` methods to wire up the client to AutoRest's service client tracing.</span></span>

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

<span data-ttu-id="4d855-158">`HttpLoggingDelegatingHandler` のログ レベルの定義は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="4d855-158">The `HttpLoggingDelegatingHandler` log levels are defined as follows:</span></span>

| <span data-ttu-id="4d855-159">トレース レベル</span><span class="sxs-lookup"><span data-stu-id="4d855-159">Trace level</span></span> | <span data-ttu-id="4d855-160">有効になるログ</span><span class="sxs-lookup"><span data-stu-id="4d855-160">Logging enabled</span></span> 
| ------------ | ---------------
| <span data-ttu-id="4d855-161">HttpLoggingDelegatingHandler.Level.None</span><span class="sxs-lookup"><span data-stu-id="4d855-161">HttpLoggingDelegatingHandler.Level.None</span></span> | <span data-ttu-id="4d855-162">出力なし</span><span class="sxs-lookup"><span data-stu-id="4d855-162">No output</span></span>
| <span data-ttu-id="4d855-163">HttpLoggingDelegatingHandler.Level.Basic</span><span class="sxs-lookup"><span data-stu-id="4d855-163">HttpLoggingDelegatingHandler.Level.Basic</span></span> | <span data-ttu-id="4d855-164">基になる REST 呼び出しの URL、応答コード、時間がログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="4d855-164">Logs the URLs to underlying REST calls, response codes and times</span></span>
| <span data-ttu-id="4d855-165">HttpLoggingDelegatingHandler.Level.Body</span><span class="sxs-lookup"><span data-stu-id="4d855-165">HttpLoggingDelegatingHandler.Level.Body</span></span> | <span data-ttu-id="4d855-166">Basic の全出力内容に加えて、REST 呼び出しの要求と応答の本文がログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="4d855-166">Everything in Basic plus request and response bodies for the REST calls</span></span>
| <span data-ttu-id="4d855-167">HttpLoggingDelegatingHandler.Level.Headers</span><span class="sxs-lookup"><span data-stu-id="4d855-167">HttpLoggingDelegatingHandler.Level.Headers</span></span> | <span data-ttu-id="4d855-168">Basic の全出力内容に加えて、REST 呼び出しの要求ヘッダーと応答ヘッダーがログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="4d855-168">Everything in Basic plus the request and response headers REST calls</span></span>
| <span data-ttu-id="4d855-169">HttpLoggingDelegatingHandler.Level.BodyAndHeaders</span><span class="sxs-lookup"><span data-stu-id="4d855-169">HttpLoggingDelegatingHandler.Level.BodyAndHeaders</span></span> | <span data-ttu-id="4d855-170">Body と Headers の両方のログ レベルの全出力内容がログに記録されます。</span><span class="sxs-lookup"><span data-stu-id="4d855-170">Everything in both Body and Headers log level</span></span>
