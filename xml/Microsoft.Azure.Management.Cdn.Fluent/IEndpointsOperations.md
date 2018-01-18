<Type Name="IEndpointsOperations" FullName="Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations">
  <TypeSignature Language="C#" Value="public interface IEndpointsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEndpointsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEndpointsOperations" />
  <TypeSignature Language="F#" Value="type IEndpointsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04e09-101">EndpointsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="04e09-101">EndpointsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, endpoint, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-102">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-102">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-103">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-103">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-104">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-104">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="endpoint">
            <span data-ttu-id="04e09-105">エンドポイントのプロパティ</span><span class="sxs-lookup"><span data-stu-id="04e09-105">Endpoint properties</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-108">指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルを新しい CDN エンドポイントを作成します。</span><span class="sxs-lookup"><span data-stu-id="04e09-108">Creates a new CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEndpointsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-112">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-112">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-113">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-113">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-114">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-114">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-117">指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルの既存の CDN エンドポイントを削除します。</span><span class="sxs-lookup"><span data-stu-id="04e09-117">Deletes an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginLoadContentWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginLoadContentWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginLoadContentWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.BeginLoadContentWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginLoadContentWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEndpointsOperations.BeginLoadContentWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, contentPaths, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-120">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-120">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-121">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-121">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-122">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-122">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="contentPaths">
            <span data-ttu-id="04e09-123">読み込まれるコンテンツへのパス。</span><span class="sxs-lookup"><span data-stu-id="04e09-123">The path to the content to be loaded.</span></span> <span data-ttu-id="04e09-124">パスは、元のファイルの相対 URL を指定します。</span><span class="sxs-lookup"><span data-stu-id="04e09-124">Path should be a relative file URL of the origin.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-127">CDN のコンテンツを事前に読み込みます。</span><span class="sxs-lookup"><span data-stu-id="04e09-127">Pre-loads a content to CDN.</span></span> <span data-ttu-id="04e09-128">Verizon プロファイルで使用できます。</span><span class="sxs-lookup"><span data-stu-id="04e09-128">Available for Verizon Profiles.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginPurgeContentWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginPurgeContentWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginPurgeContentWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.BeginPurgeContentWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPurgeContentWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEndpointsOperations.BeginPurgeContentWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, contentPaths, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-131">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-131">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-132">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-132">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-133">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-133">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="contentPaths">
            <span data-ttu-id="04e09-134">消去するコンテンツへのパス。</span><span class="sxs-lookup"><span data-stu-id="04e09-134">The path to the content to be purged.</span></span> <span data-ttu-id="04e09-135">ファイル パスまたはワイルド カード ディレクトリを記述できます。</span><span class="sxs-lookup"><span data-stu-id="04e09-135">Can describe a file path or a wild card directory.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-138">CDN からコンテンツを削除します。</span><span class="sxs-lookup"><span data-stu-id="04e09-138">Removes a content from CDN.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginStartWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginStartWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.BeginStartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.BeginStartWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-141">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-141">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-142">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-142">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-143">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-143">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-146">停止状態にある既存の CDN エンドポイントを開始します。</span><span class="sxs-lookup"><span data-stu-id="04e09-146">Starts an existing CDN endpoint that is on a stopped state.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginStopWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginStopWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.BeginStopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.BeginStopWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-150">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-150">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-151">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-151">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-152">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-152">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-155">既存の実行中の CDN エンドポイントを停止します。</span><span class="sxs-lookup"><span data-stu-id="04e09-155">Stops an existing running CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, endpointUpdateProperties, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-159">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-159">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-160">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-160">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-161">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-161">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="endpointUpdateProperties">
            <span data-ttu-id="04e09-162">エンドポイントの更新のプロパティ</span><span class="sxs-lookup"><span data-stu-id="04e09-162">Endpoint update properties</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-163">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-163">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-165">指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルでは、既存の CDN エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="04e09-165">Updates an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.</span></span> <span data-ttu-id="04e09-166">エンドポイントの作成後は、タグと配信元ホスト ヘッダーのみを更新できます。</span><span class="sxs-lookup"><span data-stu-id="04e09-166">Only tags and Origin HostHeader can be updated after creating an endpoint.</span></span> <span data-ttu-id="04e09-167">元のドメインを更新するには、Origin の更新操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="04e09-167">To update origins, use the Update Origin operation.</span></span> <span data-ttu-id="04e09-168">カスタム ドメインを更新するには、カスタム ドメインの更新操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="04e09-168">To update custom domains, use the Update Custom Domain operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner endpoint, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.CreateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, endpoint, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-172">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-172">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-173">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-173">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-174">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-174">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="endpoint">
            <span data-ttu-id="04e09-175">エンドポイントのプロパティ</span><span class="sxs-lookup"><span data-stu-id="04e09-175">Endpoint properties</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-178">指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルを新しい CDN エンドポイントを作成します。</span><span class="sxs-lookup"><span data-stu-id="04e09-178">Creates a new CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEndpointsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-182">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-182">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-183">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-183">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-184">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-184">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-185">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-187">指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルの既存の CDN エンドポイントを削除します。</span><span class="sxs-lookup"><span data-stu-id="04e09-187">Deletes an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-188">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-188">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.GetWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-190">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-190">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-191">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-191">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-192">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-192">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-193">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-195">指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルの既存の CDN エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="04e09-195">Gets an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-197">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByProfileNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt; ListByProfileNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt; ListByProfileNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.ListByProfileNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByProfileNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt;" Usage="iEndpointsOperations.ListByProfileNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="04e09-199">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="04e09-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-200">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-200">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-202">既存の CDN エンドポイントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="04e09-202">Lists existing CDN endpoints.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-203">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-204">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByProfileWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt; ListByProfileWithHttpMessagesAsync (string resourceGroupName, string profileName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt; ListByProfileWithHttpMessagesAsync(string resourceGroupName, string profileName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.ListByProfileWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByProfileWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt;" Usage="iEndpointsOperations.ListByProfileWithHttpMessagesAsync (resourceGroupName, profileName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-206">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-206">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-207">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-207">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-208">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-210">既存の CDN エンドポイントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="04e09-210">Lists existing CDN endpoints.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-211">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-211">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-212">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-212">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-213">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-213">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.ListResourceUsageNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsageNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;" Usage="iEndpointsOperations.ListResourceUsageNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="04e09-214">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="04e09-214">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-215">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-217">クォータと地理的フィルターおよび特定のエンドポイントでカスタム ドメインの使用状況を確認します。</span><span class="sxs-lookup"><span data-stu-id="04e09-217">Checks the quota and usage of geo filters and custom domains under the given endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt; ListResourceUsageWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.ListResourceUsageWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsageWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;" Usage="iEndpointsOperations.ListResourceUsageWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-221">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-221">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-222">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-222">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-223">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-223">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-224">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-224">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-226">クォータと地理的フィルターおよび特定のエンドポイントでカスタム ドメインの使用状況を確認します。</span><span class="sxs-lookup"><span data-stu-id="04e09-226">Checks the quota and usage of geo filters and custom domains under the given endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-227">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-227">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-228">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-228">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-229">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-229">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="LoadContentWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; LoadContentWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; LoadContentWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.LoadContentWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadContentWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEndpointsOperations.LoadContentWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, contentPaths, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-230">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-230">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-231">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-231">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-232">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-232">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="contentPaths">
            <span data-ttu-id="04e09-233">読み込まれるコンテンツへのパス。</span><span class="sxs-lookup"><span data-stu-id="04e09-233">The path to the content to be loaded.</span></span> <span data-ttu-id="04e09-234">パスは、元のファイルの相対 URL を指定します。</span><span class="sxs-lookup"><span data-stu-id="04e09-234">Path should be a relative file URL of the origin.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-235">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-235">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-237">CDN のコンテンツを事前に読み込みます。</span><span class="sxs-lookup"><span data-stu-id="04e09-237">Pre-loads a content to CDN.</span></span> <span data-ttu-id="04e09-238">Verizon プロファイルで使用できます。</span><span class="sxs-lookup"><span data-stu-id="04e09-238">Available for Verizon Profiles.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-239">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-239">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-240">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-240">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PurgeContentWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeContentWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeContentWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.PurgeContentWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeContentWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEndpointsOperations.PurgeContentWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, contentPaths, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-241">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-241">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-242">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-242">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-243">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-243">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="contentPaths">
            <span data-ttu-id="04e09-244">消去するコンテンツへのパス。</span><span class="sxs-lookup"><span data-stu-id="04e09-244">The path to the content to be purged.</span></span> <span data-ttu-id="04e09-245">ファイル パスまたはワイルド カード ディレクトリを記述できます。</span><span class="sxs-lookup"><span data-stu-id="04e09-245">Can describe a file path or a wild card directory.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-246">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-246">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-247">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-248">CDN からコンテンツを削除します。</span><span class="sxs-lookup"><span data-stu-id="04e09-248">Removes a content from CDN.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-249">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-249">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-250">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-250">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; StartWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; StartWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.StartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.StartWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-251">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-251">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-252">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-252">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-253">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-253">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-254">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-254">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-256">停止状態にある既存の CDN エンドポイントを開始します。</span><span class="sxs-lookup"><span data-stu-id="04e09-256">Starts an existing CDN endpoint that is on a stopped state.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-258">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-259">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-259">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; StopWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; StopWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.StopWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.StopWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-260">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-260">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-261">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-261">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-262">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-262">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-263">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-263">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-264">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-265">既存の実行中の CDN エンドポイントを停止します。</span><span class="sxs-lookup"><span data-stu-id="04e09-265">Stops an existing running CDN endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-266">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-266">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-267">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-267">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-268">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-268">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner endpointUpdateProperties, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, endpointUpdateProperties, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-269">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-269">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-270">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-270">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-271">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-271">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="endpointUpdateProperties">
            <span data-ttu-id="04e09-272">エンドポイントの更新のプロパティ</span><span class="sxs-lookup"><span data-stu-id="04e09-272">Endpoint update properties</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-273">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-273">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-274">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-274">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-275">指定したエンドポイント名、型指定されたサブスクリプション、リソース グループとプロファイルでは、既存の CDN エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="04e09-275">Updates an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.</span></span> <span data-ttu-id="04e09-276">エンドポイントの作成後は、タグと配信元ホスト ヘッダーのみを更新できます。</span><span class="sxs-lookup"><span data-stu-id="04e09-276">Only tags and Origin HostHeader can be updated after creating an endpoint.</span></span> <span data-ttu-id="04e09-277">元のドメインを更新するには、Origin の更新操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="04e09-277">To update origins, use the Update Origin operation.</span></span> <span data-ttu-id="04e09-278">カスタム ドメインを更新するには、カスタム ドメインの更新操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="04e09-278">To update custom domains, use the Update Custom Domain operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-279">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-279">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-280">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-280">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-281">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-281">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomainWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt;&gt; ValidateCustomDomainWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string hostName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt;&gt; ValidateCustomDomainWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string hostName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IEndpointsOperations.ValidateCustomDomainWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateCustomDomainWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt;&gt;" Usage="iEndpointsOperations.ValidateCustomDomainWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, hostName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainOutputInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04e09-282">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-282">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="04e09-283">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-283">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="04e09-284">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="04e09-284">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="04e09-285">カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="04e09-285">The host name of the custom domain.</span></span> <span data-ttu-id="04e09-286">ドメイン名である必要があります。</span><span class="sxs-lookup"><span data-stu-id="04e09-286">Must be a domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="04e09-287">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="04e09-287">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04e09-288">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04e09-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04e09-289">DNS の適切な CDN エンドポイントにマッピングされていることを確認するカスタム ドメインのマッピングを検証します。</span><span class="sxs-lookup"><span data-stu-id="04e09-289">Validates the custom domain mapping to ensure it maps to the correct CDN endpoint in DNS.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="04e09-290">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-290">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="04e09-291">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-291">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04e09-292">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="04e09-292">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>