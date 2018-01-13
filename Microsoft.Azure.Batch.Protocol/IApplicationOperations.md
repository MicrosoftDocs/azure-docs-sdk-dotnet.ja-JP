<Type Name="IApplicationOperations" FullName="Microsoft.Azure.Batch.Protocol.IApplicationOperations">
  <TypeSignature Language="C#" Value="public interface IApplicationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IApplicationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationOperations" />
  <TypeSignature Language="F#" Value="type IApplicationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2fe3c-101">ApplicationOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-101">ApplicationOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string applicationId, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string applicationId, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IApplicationOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt;" Usage="iApplicationOperations.GetWithHttpMessagesAsync (applicationId, applicationGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="applicationGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationId">
            <span data-ttu-id="2fe3c-102">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-102">The ID of the application.</span></span>
            </param>
        <param name="applicationGetOptions">
            <span data-ttu-id="2fe3c-103">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="2fe3c-103">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="2fe3c-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2fe3c-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2fe3c-106">指定されたアプリケーションに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-106">Gets information about the specified application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2fe3c-107">この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-107">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="2fe3c-108">管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-108">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="2fe3c-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="2fe3c-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2fe3c-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IApplicationOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;" Usage="iApplicationOperations.ListNextWithHttpMessagesAsync (nextPageLink, applicationListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="applicationListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="2fe3c-112">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-112">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="applicationListNextOptions">
            <span data-ttu-id="2fe3c-113">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="2fe3c-113">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="2fe3c-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2fe3c-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2fe3c-116">すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-116">Lists all of the applications available in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2fe3c-117">この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-117">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="2fe3c-118">管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-118">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="2fe3c-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="2fe3c-120">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2fe3c-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IApplicationOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;" Usage="iApplicationOperations.ListWithHttpMessagesAsync (applicationListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationListOptions">
            <span data-ttu-id="2fe3c-122">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="2fe3c-122">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="2fe3c-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2fe3c-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2fe3c-125">すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-125">Lists all of the applications available in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2fe3c-126">この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-126">This operation returns only applications and versions that are available for use on compute nodes; that is, that can be used in an application package reference.</span></span> <span data-ttu-id="2fe3c-127">管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-127">For administrator information about applications and versions that are not yet available to compute nodes, use the Azure portal or the Azure Resource Manager API.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="2fe3c-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="2fe3c-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2fe3c-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe3c-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>