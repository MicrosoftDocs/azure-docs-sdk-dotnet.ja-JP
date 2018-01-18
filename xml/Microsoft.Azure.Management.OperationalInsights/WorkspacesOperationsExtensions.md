<Type Name="WorkspacesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WorkspacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WorkspacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WorkspacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WorkspacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1983b-101">WorkspacesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1983b-101">Extension methods for WorkspacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace BeginCreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace BeginCreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As Workspace) As Workspace" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-103">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-103">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-104">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-104">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-105">作成またはワークスペースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-105">The parameters required to create or update a workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-106">作成またはワークスペースを更新します。</span><span class="sxs-lookup"><span data-stu-id="1983b-106">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-108">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-108">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-109">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-109">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-110">作成またはワークスペースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-110">The parameters required to create or update a workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-112">作成またはワークスペースを更新します。</span><span class="sxs-lookup"><span data-stu-id="1983b-112">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse BeginGetSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse BeginGetSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As SearchParameters) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member BeginGetSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResults (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-114">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-114">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-115">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-115">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-116">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-116">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-117">検索クエリを実行するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-117">The parameters required to execute a search query.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-118">指定されたワークスペースの検索を送信します。</span><span class="sxs-lookup"><span data-stu-id="1983b-118">Submit a search for a given workspace.</span></span> <span data-ttu-id="1983b-119">応答は、検索を追跡するための id が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1983b-119">The response will contain an id to track the search.</span></span> <span data-ttu-id="1983b-120">ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1983b-120">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; BeginGetSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; BeginGetSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResultsAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;BeginGetSearchResultsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-122">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-122">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-123">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-124">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-124">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-125">検索クエリを実行するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-125">The parameters required to execute a search query.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-127">指定されたワークスペースの検索を送信します。</span><span class="sxs-lookup"><span data-stu-id="1983b-127">Submit a search for a given workspace.</span></span> <span data-ttu-id="1983b-128">応答は、検索を追跡するための id が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1983b-128">The response will contain an id to track the search.</span></span> <span data-ttu-id="1983b-129">ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1983b-129">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As Workspace) As Workspace" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-131">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-131">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-132">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-132">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-133">作成またはワークスペースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-133">The parameters required to create or update a workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-134">作成またはワークスペースを更新します。</span><span class="sxs-lookup"><span data-stu-id="1983b-134">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-136">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-136">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-137">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-137">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-138">作成またはワークスペースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-138">The parameters required to create or update a workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-140">作成またはワークスペースを更新します。</span><span class="sxs-lookup"><span data-stu-id="1983b-140">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-142">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-142">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-143">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-143">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-144">ワークスペースのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="1983b-144">Deletes a workspace instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;DeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-146">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-146">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-147">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-147">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-149">ワークスペースのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="1983b-149">Deletes a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableIntelligencePack">
      <MemberSignature Language="C#" Value="public static void DisableIntelligencePack (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DisableIntelligencePack(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePack(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DisableIntelligencePack (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, intelligencePackName As String)" />
      <MemberSignature Language="F#" Value="static member DisableIntelligencePack : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePack (operations, resourceGroupName, workspaceName, intelligencePackName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-151">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-151">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-152">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-152">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-153">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-153">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="1983b-154">無効にするインテリジェンス パックの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-154">The name of the intelligence pack to be disabled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-155">指定されたワークスペースのインテリジェンス パックを無効にします。</span><span class="sxs-lookup"><span data-stu-id="1983b-155">Disables an intelligence pack for a given workspace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableIntelligencePackAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableIntelligencePackAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableIntelligencePackAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePackAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableIntelligencePackAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePackAsync (operations, resourceGroupName, workspaceName, intelligencePackName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;DisableIntelligencePackAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-157">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-157">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-158">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-158">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-159">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-159">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="1983b-160">無効にするインテリジェンス パックの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-160">The name of the intelligence pack to be disabled.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-162">指定されたワークスペースのインテリジェンス パックを無効にします。</span><span class="sxs-lookup"><span data-stu-id="1983b-162">Disables an intelligence pack for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIntelligencePack">
      <MemberSignature Language="C#" Value="public static void EnableIntelligencePack (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnableIntelligencePack(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePack(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub EnableIntelligencePack (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, intelligencePackName As String)" />
      <MemberSignature Language="F#" Value="static member EnableIntelligencePack : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePack (operations, resourceGroupName, workspaceName, intelligencePackName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-164">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-164">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-165">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-165">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-166">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-166">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="1983b-167">有効にするインテリジェンス パックの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-167">The name of the intelligence pack to be enabled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-168">指定されたワークスペースのインテリジェンス パックを有効にします。</span><span class="sxs-lookup"><span data-stu-id="1983b-168">Enables an intelligence pack for a given workspace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIntelligencePackAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task EnableIntelligencePackAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task EnableIntelligencePackAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePackAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableIntelligencePackAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePackAsync (operations, resourceGroupName, workspaceName, intelligencePackName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;EnableIntelligencePackAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-170">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-170">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-171">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-171">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-172">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-172">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="1983b-173">有効にするインテリジェンス パックの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-173">The name of the intelligence pack to be enabled.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-175">指定されたワークスペースのインテリジェンス パックを有効にします。</span><span class="sxs-lookup"><span data-stu-id="1983b-175">Enables an intelligence pack for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace Get (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace Get(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As Workspace" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Get (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-177">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-177">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-178">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-178">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-179">ワークスペースのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-179">Gets a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-181">ワークスペースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1983b-181">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-182">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-182">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-184">ワークスペースのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-184">Gets a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse GetSchema (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse GetSchema(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchema(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSchema (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As SearchGetSchemaResponse" />
      <MemberSignature Language="F#" Value="static member GetSchema : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchema (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-186">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-186">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-187">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-187">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-188">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-188">Log Analytics workspace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-189">指定されたワークスペースのスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-189">Gets the schema for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt; GetSchemaAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt; GetSchemaAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchemaAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSchemaAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchemaAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSchemaAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-191">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-191">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-192">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-192">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-193">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-193">Log Analytics workspace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-195">指定されたワークスペースのスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-195">Gets the schema for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As SearchParameters) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member GetSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResults (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-196">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-197">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-197">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-198">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-198">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-199">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-199">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-200">検索クエリを実行するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-200">The parameters required to execute a search query.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-201">指定されたワークスペースの検索を送信します。</span><span class="sxs-lookup"><span data-stu-id="1983b-201">Submit a search for a given workspace.</span></span> <span data-ttu-id="1983b-202">応答は、検索を追跡するための id が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1983b-202">The response will contain an id to track the search.</span></span> <span data-ttu-id="1983b-203">ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1983b-203">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResultsAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSearchResultsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-205">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-205">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-206">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-206">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-207">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-207">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1983b-208">検索クエリを実行するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1983b-208">The parameters required to execute a search query.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-210">指定されたワークスペースの検索を送信します。</span><span class="sxs-lookup"><span data-stu-id="1983b-210">Submit a search for a given workspace.</span></span> <span data-ttu-id="1983b-211">応答は、検索を追跡するための id が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1983b-211">The response will contain an id to track the search.</span></span> <span data-ttu-id="1983b-212">ユーザーは、検索の状態をポーリングし、検索が完了までに時間を取る場合、後でフル検索結果を取得する、id を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1983b-212">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys GetSharedKeys (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys GetSharedKeys(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeys(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSharedKeys (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As SharedKeys" />
      <MemberSignature Language="F#" Value="static member GetSharedKeys : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeys (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-214">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-214">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-215">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-215">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-216">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-216">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-217">ワークスペースの共有キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-217">Gets the shared keys for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt; GetSharedKeysAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt; GetSharedKeysAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeysAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSharedKeysAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeysAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSharedKeysAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-219">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-219">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-220">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-220">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-221">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-221">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-223">ワークスペースの共有キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-223">Gets the shared keys for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; List (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; List(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.List(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWorkspacesOperations) As IEnumerable(Of Workspace)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-224">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-224">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-225">サブスクリプション内のワークスペースを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-225">Gets the workspaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-226">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-228">サブスクリプション内のワークスペースを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-228">Gets the workspaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; ListByResourceGroup (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; ListByResourceGroup(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IWorkspacesOperations, resourceGroupName As String) As IEnumerable(Of Workspace)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-230">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-230">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-231">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-231">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-232">リソース グループ内のワークスペースを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-232">Gets workspaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-234">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-234">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-235">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-235">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-237">リソース グループ内のワークスペースを取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-237">Gets workspaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListIntelligencePacks">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt; ListIntelligencePacks (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt; ListIntelligencePacks(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacks(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListIntelligencePacks (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IList(Of IntelligencePack)" />
      <MemberSignature Language="F#" Value="static member ListIntelligencePacks : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacks (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-238">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-238">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-239">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-239">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-240">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-240">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-241">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-241">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-242">リスト、すべてのインテリジェンス パック可能かどうか有効または無効にした、特定のワークスペースのします。</span><span class="sxs-lookup"><span data-stu-id="1983b-242">Lists all the intelligence packs possible and whether they are enabled or disabled for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListIntelligencePacksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt; ListIntelligencePacksAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt; ListIntelligencePacksAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacksAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListIntelligencePacksAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacksAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListIntelligencePacksAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-244">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-244">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-245">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-245">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-246">ログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-246">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-247">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-248">リスト、すべてのインテリジェンス パック可能かどうか有効または無効にした、特定のワークスペースのします。</span><span class="sxs-lookup"><span data-stu-id="1983b-248">Lists all the intelligence packs possible and whether they are enabled or disabled for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkTargets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt; ListLinkTargets (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt; ListLinkTargets(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargets(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLinkTargets (operations As IWorkspacesOperations) As IList(Of LinkTarget)" />
      <MemberSignature Language="F#" Value="static member ListLinkTargets : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargets operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-249">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-250">一覧を取得する現在のユーザーがいるワークスペースの管理者特権とは、Azure サブスクリプションに関連付けられていません。</span><span class="sxs-lookup"><span data-stu-id="1983b-250">Get a list of workspaces which the current user has administrator privileges and are not associated with an Azure Subscription.</span></span> <span data-ttu-id="1983b-251">Url の subscriptionId パラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="1983b-251">The subscriptionId parameter in the Url is ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkTargetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt; ListLinkTargetsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt; ListLinkTargetsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargetsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLinkTargetsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargetsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListLinkTargetsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-252">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-253">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-254">一覧を取得する現在のユーザーがいるワークスペースの管理者特権とは、Azure サブスクリプションに関連付けられていません。</span><span class="sxs-lookup"><span data-stu-id="1983b-254">Get a list of workspaces which the current user has administrator privileges and are not associated with an Azure Subscription.</span></span> <span data-ttu-id="1983b-255">Url の subscriptionId パラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="1983b-255">The subscriptionId parameter in the Url is ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListManagementGroups">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt; ListManagementGroups (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt; ListManagementGroups(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroups(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListManagementGroups (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of ManagementGroup)" />
      <MemberSignature Language="F#" Value="static member ListManagementGroups : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroups (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-257">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-257">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-258">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-258">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-259">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-259">The name of the workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-260">ワークスペースに接続されている管理グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-260">Gets a list of management groups connected to a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListManagementGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt; ListManagementGroupsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt; ListManagementGroupsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroupsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListManagementGroupsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroupsAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListManagementGroupsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-261">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-262">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-262">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-263">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-263">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-264">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-264">The name of the workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-265">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-265">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-266">ワークスペースに接続されている管理グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-266">Gets a list of management groups connected to a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsages">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt; ListUsages (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt; ListUsages(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsages(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsages (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of UsageMetric)" />
      <MemberSignature Language="F#" Value="static member ListUsages : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsages (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-268">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-268">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-269">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-269">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-270">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-270">The name of the workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-271">ワークスペースの使用状況メトリックの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-271">Gets a list of usage metrics for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListUsagesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-272">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-273">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-273">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-274">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-274">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-275">ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1983b-275">The name of the workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-276">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-277">ワークスペースの使用状況メトリックの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-277">Gets a list of usage metrics for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse UpdateSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse UpdateSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, id As String) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member UpdateSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResults (operations, resourceGroupName, workspaceName, id)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-278">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-278">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-279">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-279">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-280">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-280">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-281">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-281">Log Analytics workspace name</span></span>
            </param>
        <param name="id">
            <span data-ttu-id="1983b-282">検索結果の更新を持っているの id。</span><span class="sxs-lookup"><span data-stu-id="1983b-282">The id of the search that will have results updated.</span></span> <span data-ttu-id="1983b-283">GetResults 呼び出しの応答から id を取得できます。</span><span class="sxs-lookup"><span data-stu-id="1983b-283">You can get the id from the response of the GetResults call.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-284">更新された特定の検索クエリの検索結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-284">Gets updated search results for a given search query.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; UpdateSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; UpdateSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResultsAsync (operations, resourceGroupName, workspaceName, id, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;UpdateSearchResultsAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1983b-285">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1983b-285">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1983b-286">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1983b-286">The name of the resource group to get.</span></span> <span data-ttu-id="1983b-287">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1983b-287">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1983b-288">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="1983b-288">Log Analytics workspace name</span></span>
            </param>
        <param name="id">
            <span data-ttu-id="1983b-289">検索結果の更新を持っているの id。</span><span class="sxs-lookup"><span data-stu-id="1983b-289">The id of the search that will have results updated.</span></span> <span data-ttu-id="1983b-290">GetResults 呼び出しの応答から id を取得できます。</span><span class="sxs-lookup"><span data-stu-id="1983b-290">You can get the id from the response of the GetResults call.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1983b-291">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1983b-291">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1983b-292">更新された特定の検索クエリの検索結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="1983b-292">Gets updated search results for a given search query.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>