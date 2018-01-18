<Type Name="IRedisOperations" FullName="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations">
  <TypeSignature Language="C#" Value="public interface IRedisOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRedisOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRedisOperations" />
  <TypeSignature Language="F#" Value="type IRedisOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6ef6c-101">RedisOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-101">RedisOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="iRedisOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-102">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-103">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-103">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-104">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-104">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-107">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-107">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-111">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-112">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-112">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-115">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-115">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginExportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginExportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginExportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.BeginExportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginExportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.BeginExportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-118">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-119">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-119">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-120">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-120">Parameters for Redis export operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-123">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-123">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginImportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginImportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginImportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.BeginImportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginImportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.BeginImportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-126">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-126">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-127">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-127">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-128">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-128">Parameters for Redis import operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-131">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-131">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="iRedisOperations.CreateWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-134">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-135">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-135">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-136">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-136">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-139">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-139">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.DeleteWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-143">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-144">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-144">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-145">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-145">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-147">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-147">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ExportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ExportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ExportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.ExportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-150">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-150">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-151">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-151">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-152">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-152">Parameters for Redis export operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-155">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-155">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-157">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-157">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ForceRebootWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;&gt; ForceRebootWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;&gt; ForceRebootWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ForceRebootWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ForceRebootWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;&gt;" Usage="iRedisOperations.ForceRebootWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-158">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-158">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-159">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-159">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-160">ノードを再起動する Redis を指定します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-160">Specifies which Redis node(s) to reboot.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-163">指定した Redis ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-163">Reboot specified Redis node(s).</span></span> <span data-ttu-id="6ef6c-164">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-164">This operation requires write permission to the cache resource.</span></span> <span data-ttu-id="6ef6c-165">データ損失の可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-165">There can be potential data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-166">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-167">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-168">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="iRedisOperations.GetWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-169">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-170">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-170">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-171">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-171">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-173">Redis cache (リソースの説明) を取得します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-173">Gets a Redis cache (resource description).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-174">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-174">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-175">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-175">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-176">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ImportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ImportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ImportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ImportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.ImportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-177">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-177">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-178">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-178">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-179">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-179">Parameters for Redis import operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-182">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-182">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-184">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-184">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;" Usage="iRedisOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="6ef6c-185">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-185">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-186">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-186">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-188">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-188">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-189">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-190">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-190">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-191">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-191">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;" Usage="iRedisOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-192">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-192">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-193">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-195">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-195">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-197">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt;" Usage="iRedisOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-199">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-199">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-200">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-200">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-201">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-203">Redis cache のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-203">Retrieve a Redis cache's access keys.</span></span> <span data-ttu-id="6ef6c-204">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-204">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;" Usage="iRedisOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="6ef6c-208">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-209">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-209">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-211">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-211">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-214">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;" Usage="iRedisOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-215">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-217">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-217">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt; RegenerateKeyWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt; RegenerateKeyWithHttpMessagesAsync(string resourceGroupName, string name, valuetype Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.RegenerateKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt;" Usage="iRedisOperations.RegenerateKeyWithHttpMessagesAsync (resourceGroupName, name, keyType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-221">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-221">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-222">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-222">The name of the Redis cache.</span></span>
            </param>
        <param name="keyType">
            <span data-ttu-id="6ef6c-223">Redis アクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-223">The Redis access key to regenerate.</span></span> <span data-ttu-id="6ef6c-224">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-224">Possible values include: 'Primary', 'Secondary'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-225">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-225">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-227">Redis cache のアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-227">Regenerate Redis cache's access keys.</span></span> <span data-ttu-id="6ef6c-228">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-228">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-229">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-229">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-230">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-230">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-231">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-231">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.IRedisOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="iRedisOperations.UpdateWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6ef6c-232">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-232">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="6ef6c-233">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-233">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6ef6c-234">更新プログラムの Redis 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-234">Parameters supplied to the Update Redis operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6ef6c-235">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-235">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6ef6c-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ef6c-237">既存の Redis キャッシュを更新します。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-237">Update an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6ef6c-238">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-238">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6ef6c-239">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-239">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef6c-240">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef6c-240">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>