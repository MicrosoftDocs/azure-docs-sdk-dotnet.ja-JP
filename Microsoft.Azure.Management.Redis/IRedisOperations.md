<Type Name="IRedisOperations" FullName="Microsoft.Azure.Management.Redis.IRedisOperations">
  <TypeSignature Language="C#" Value="public interface IRedisOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRedisOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.IRedisOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRedisOperations" />
  <TypeSignature Language="F#" Value="type IRedisOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="01391-101">RedisOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="01391-101">RedisOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.RedisCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="iRedisOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-102">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-103">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-103">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-104">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="01391-104">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-107">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="01391-107">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="01391-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-111">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-112">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-112">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-115">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="01391-115">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginExportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginExportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginExportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.BeginExportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ExportRDBParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginExportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.ExportRDBParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.BeginExportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-118">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-119">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-119">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-120">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01391-120">Parameters for Redis export operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-123">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="01391-123">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginImportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginImportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginImportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.BeginImportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ImportRDBParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginImportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.ImportRDBParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.BeginImportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-126">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-126">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-127">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-127">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-128">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01391-128">Parameters for Redis import operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-131">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="01391-131">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.RedisCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="iRedisOperations.CreateWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-134">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-135">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-135">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-136">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="01391-136">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-139">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="01391-139">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.DeleteWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="01391-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-143">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-144">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-144">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-145">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-145">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-147">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="01391-147">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ExportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ExportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ExportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ExportRDBParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.ExportRDBParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.ExportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-150">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-150">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-151">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-151">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-152">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01391-152">Parameters for Redis export operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-155">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="01391-155">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-157">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-157">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ForceRebootWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt;&gt; ForceRebootWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisRebootParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt;&gt; ForceRebootWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisRebootParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ForceRebootWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisRebootParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ForceRebootWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.RedisRebootParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt;&gt;" Usage="iRedisOperations.ForceRebootWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisRebootParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-158">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-158">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-159">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-159">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-160">ノードを再起動する Redis を指定します。</span><span class="sxs-lookup"><span data-stu-id="01391-160">Specifies which Redis node(s) to reboot.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-163">指定した Redis ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="01391-163">Reboot specified Redis node(s).</span></span> <span data-ttu-id="01391-164">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="01391-164">This operation requires write permission to the cache resource.</span></span> <span data-ttu-id="01391-165">データ損失の可能性があります。</span><span class="sxs-lookup"><span data-stu-id="01391-165">There can be potential data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-166">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-167">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-168">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="iRedisOperations.GetWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-169">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-170">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-170">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-171">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-171">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-173">Redis cache (リソースの説明) を取得します。</span><span class="sxs-lookup"><span data-stu-id="01391-173">Gets a Redis cache (resource description).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-174">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-174">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-175">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-175">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-176">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ImportDataWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ImportDataWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ImportDataWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ImportDataWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.ImportRDBParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDataWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.ImportRDBParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRedisOperations.ImportDataWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-177">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-177">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-178">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-178">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-179">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01391-179">Parameters for Redis import operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-182">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="01391-182">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-184">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-184">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;" Usage="iRedisOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="01391-185">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="01391-185">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-186">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-186">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-188">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="01391-188">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-189">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-190">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-190">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-191">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-191">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;" Usage="iRedisOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-192">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-192">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-193">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-195">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="01391-195">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-197">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt;" Usage="iRedisOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-199">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-199">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-200">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-200">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-201">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-203">Redis cache のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="01391-203">Retrieve a Redis cache's access keys.</span></span> <span data-ttu-id="01391-204">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="01391-204">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;" Usage="iRedisOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="01391-208">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="01391-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-209">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-209">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-211">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="01391-211">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-214">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;" Usage="iRedisOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="01391-215">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-217">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="01391-217">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt; RegenerateKeyWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt; RegenerateKeyWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.RegenerateKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt;" Usage="iRedisOperations.RegenerateKeyWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-221">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-221">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-222">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-222">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-223">再生成するキーを指定します。</span><span class="sxs-lookup"><span data-stu-id="01391-223">Specifies which key to regenerate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-224">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-224">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-226">Redis cache のアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="01391-226">Regenerate Redis cache's access keys.</span></span> <span data-ttu-id="01391-227">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="01391-227">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-228">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-228">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-229">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-229">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-230">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-230">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IRedisOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="iRedisOperations.UpdateWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="01391-231">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01391-231">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="01391-232">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="01391-232">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01391-233">更新プログラムの Redis 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="01391-233">Parameters supplied to the Update Redis operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="01391-234">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="01391-234">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01391-235">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01391-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01391-236">既存の Redis キャッシュを更新します。</span><span class="sxs-lookup"><span data-stu-id="01391-236">Update an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="01391-237">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-237">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="01391-238">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-238">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="01391-239">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="01391-239">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>