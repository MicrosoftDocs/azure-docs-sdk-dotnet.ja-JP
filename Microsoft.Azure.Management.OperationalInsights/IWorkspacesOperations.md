<Type Name="IWorkspacesOperations" FullName="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations">
  <TypeSignature Language="C#" Value="public interface IWorkspacesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWorkspacesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWorkspacesOperations" />
  <TypeSignature Language="F#" Value="type IWorkspacesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="63c3e-101">WorkspacesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-101">WorkspacesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="iWorkspacesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, workspaceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-102">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="63c3e-102">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-103">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-103">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63c3e-104">作成またはワークスペースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="63c3e-104">The parameters required to create or update a workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-107">作成またはワークスペースを更新します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-107">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginGetSearchResultsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; BeginGetSearchResultsWithHttpMessagesAsync (string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; BeginGetSearchResultsWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.BeginGetSearchResultsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetSearchResultsWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;" Usage="iWorkspacesOperations.BeginGetSearchResultsWithHttpMessagesAsync (resourceGroupName, workspaceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-111">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-111">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-112">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-112">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-113">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="63c3e-113">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63c3e-114">検索クエリを実行するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="63c3e-114">The parameters required to execute a search query.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-117">指定されたワークスペースの検索を送信します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-117">Submit a search for a given workspace.</span></span> <span data-ttu-id="63c3e-118">応答は、検索を追跡するための id が含まれます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-118">The response will contain an id to track the search.</span></span> <span data-ttu-id="63c3e-119">ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-119">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="iWorkspacesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, workspaceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-123">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="63c3e-123">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-124">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-124">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63c3e-125">作成またはワークスペースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="63c3e-125">The parameters required to create or update a workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-128">作成またはワークスペースを更新します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-128">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWorkspacesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-132">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="63c3e-132">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-133">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-133">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-136">ワークスペースのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-136">Deletes a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-138">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableIntelligencePackWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DisableIntelligencePackWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string intelligencePackName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DisableIntelligencePackWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string intelligencePackName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.DisableIntelligencePackWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableIntelligencePackWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWorkspacesOperations.DisableIntelligencePackWithHttpMessagesAsync (resourceGroupName, workspaceName, intelligencePackName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-139">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-139">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-140">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-140">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-141">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-141">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="63c3e-142">無効にするインテリジェンス パックの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-142">The name of the intelligence pack to be disabled.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-145">指定されたワークスペースのインテリジェンス パックを無効にします。</span><span class="sxs-lookup"><span data-stu-id="63c3e-145">Disables an intelligence pack for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-146">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableIntelligencePackWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; EnableIntelligencePackWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string intelligencePackName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; EnableIntelligencePackWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string intelligencePackName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.EnableIntelligencePackWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableIntelligencePackWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWorkspacesOperations.EnableIntelligencePackWithHttpMessagesAsync (resourceGroupName, workspaceName, intelligencePackName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-148">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-148">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-149">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-149">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-150">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-150">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="63c3e-151">有効にするインテリジェンス パックの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-151">The name of the intelligence pack to be enabled.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-152">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-152">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-154">指定されたワークスペースのインテリジェンス パックを有効にします。</span><span class="sxs-lookup"><span data-stu-id="63c3e-154">Enables an intelligence pack for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-155">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;&gt; GetSchemaWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;&gt; GetSchemaWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.GetSchemaWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSchemaWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;&gt;" Usage="iWorkspacesOperations.GetSchemaWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-157">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-157">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-158">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-158">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-159">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="63c3e-159">Log Analytics workspace name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-162">指定されたワークスペースのスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-162">Gets the schema for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetSearchResultsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; GetSearchResultsWithHttpMessagesAsync (string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; GetSearchResultsWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.GetSearchResultsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSearchResultsWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;" Usage="iWorkspacesOperations.GetSearchResultsWithHttpMessagesAsync (resourceGroupName, workspaceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-166">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-166">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-167">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-167">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-168">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="63c3e-168">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63c3e-169">検索クエリを実行するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="63c3e-169">The parameters required to execute a search query.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-172">指定されたワークスペースの検索を送信します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-172">Submit a search for a given workspace.</span></span> <span data-ttu-id="63c3e-173">応答は、検索を追跡するための id が含まれます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-173">The response will contain an id to track the search.</span></span> <span data-ttu-id="63c3e-174">ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-174">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-175">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-175">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-176">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-176">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-177">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-177">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;&gt; GetSharedKeysWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;&gt; GetSharedKeysWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.GetSharedKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSharedKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;&gt;" Usage="iWorkspacesOperations.GetSharedKeysWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-178">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-178">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-179">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-179">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-180">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-180">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-181">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-181">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-183">ワークスペースの共有キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-183">Gets the shared keys for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-184">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-184">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-185">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-185">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="iWorkspacesOperations.GetWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-187">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="63c3e-187">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-188">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-188">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-191">ワークスペースのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-191">Gets a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-192">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-193">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-193">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-194">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-194">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt;" Usage="iWorkspacesOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-195">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-195">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-196">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-196">The name is case insensitive.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-197">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-199">リソース グループ内のワークスペースを取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-199">Gets workspaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-200">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-201">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-202">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListIntelligencePacksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;&gt; ListIntelligencePacksWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;&gt; ListIntelligencePacksWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.ListIntelligencePacksWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListIntelligencePacksWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;&gt;" Usage="iWorkspacesOperations.ListIntelligencePacksWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-203">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-203">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-204">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-204">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-205">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-205">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-206">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-206">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-208">リスト、すべてのインテリジェンス パック可能かどうか有効または無効にした、特定のワークスペースのします。</span><span class="sxs-lookup"><span data-stu-id="63c3e-208">Lists all the intelligence packs possible and whether they are enabled or disabled for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-209">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-209">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-210">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-210">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-211">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-211">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListLinkTargetsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;&gt; ListLinkTargetsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;&gt; ListLinkTargetsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.ListLinkTargetsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListLinkTargetsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;&gt;" Usage="iWorkspacesOperations.ListLinkTargetsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-212">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-212">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-214">一覧を取得する現在のユーザーがいるワークスペースの管理者特権とは、Azure サブスクリプションに関連付けられていません。</span><span class="sxs-lookup"><span data-stu-id="63c3e-214">Get a list of workspaces which the current user has administrator privileges and are not associated with an Azure Subscription.</span></span> <span data-ttu-id="63c3e-215">Url の subscriptionId パラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-215">The subscriptionId parameter in the Url is ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-216">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-216">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-217">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-217">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-218">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-218">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListManagementGroupsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;&gt; ListManagementGroupsWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;&gt; ListManagementGroupsWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.ListManagementGroupsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListManagementGroupsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;&gt;" Usage="iWorkspacesOperations.ListManagementGroupsWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-219">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-219">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-220">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-220">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-221">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-221">The name of the workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-222">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-222">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-223">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-224">ワークスペースに接続されている管理グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-224">Gets a list of management groups connected to a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-225">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-225">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-226">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-226">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-227">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-227">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;&gt; ListUsagesWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;&gt; ListUsagesWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.ListUsagesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsagesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;&gt;" Usage="iWorkspacesOperations.ListUsagesWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-228">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-228">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-229">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-229">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-230">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="63c3e-230">The name of the workspace.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-231">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-231">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-232">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-233">ワークスペースの使用状況メトリックの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-233">Gets a list of usage metrics for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-234">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-234">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-235">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-235">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-236">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-236">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt;" Usage="iWorkspacesOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-237">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-237">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-239">サブスクリプション内のワークスペースを取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-239">Gets the workspaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-240">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-240">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-241">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-241">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-242">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-242">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateSearchResultsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; UpdateSearchResultsWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string id, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; UpdateSearchResultsWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string id, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations.UpdateSearchResultsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSearchResultsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;" Usage="iWorkspacesOperations.UpdateSearchResultsWithHttpMessagesAsync (resourceGroupName, workspaceName, id, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="63c3e-243">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63c3e-243">The name of the resource group to get.</span></span> <span data-ttu-id="63c3e-244">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-244">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="63c3e-245">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="63c3e-245">Log Analytics workspace name</span></span>
            </param>
        <param name="id">
            <span data-ttu-id="63c3e-246">検索結果の更新を持っているの id。</span><span class="sxs-lookup"><span data-stu-id="63c3e-246">The id of the search that will have results updated.</span></span> <span data-ttu-id="63c3e-247">GetResults 呼び出しの応答から id を取得できます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-247">You can get the id from the response of the GetResults call.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="63c3e-248">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-248">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63c3e-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63c3e-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63c3e-250">更新された特定の検索クエリの検索結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="63c3e-250">Gets updated search results for a given search query.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="63c3e-251">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-251">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="63c3e-252">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-252">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="63c3e-253">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="63c3e-253">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>