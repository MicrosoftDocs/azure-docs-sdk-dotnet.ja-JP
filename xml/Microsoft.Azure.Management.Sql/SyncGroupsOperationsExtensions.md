<Type Name="SyncGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SyncGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SyncGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SyncGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SyncGroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a1b1a-101">SyncGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-101">Extension methods for SyncGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-106">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-106">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-107">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-107">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-108">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-108">The requested sync group resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-109">作成するか、同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-109">Creates or updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-111">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-112">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-113">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-113">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-114">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-114">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-115">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-115">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-116">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-116">The requested sync group resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-118">作成するか、同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-118">Creates or updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-120">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-120">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-121">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-121">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-122">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-122">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-123">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-123">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-124">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-124">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-125">同期グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-125">Deletes a sync group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-127">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-127">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-128">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-129">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-129">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-130">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-130">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-131">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-131">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-133">同期グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-133">Deletes a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshHubSchema">
      <MemberSignature Language="C#" Value="public static void BeginRefreshHubSchema (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginRefreshHubSchema(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchema(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginRefreshHubSchema (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshHubSchema : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-135">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-136">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-137">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-137">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-138">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-138">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-139">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-139">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-140">ハブ データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-140">Refreshes a hub database schema.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshHubSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginRefreshHubSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginRefreshHubSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchemaAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshHubSchemaAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginRefreshHubSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginRefreshHubSchemaAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-142">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-142">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-143">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-143">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-144">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-144">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-145">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-145">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-146">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-146">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-148">ハブ データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-148">Refreshes a hub database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup BeginUpdate (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup BeginUpdate(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-150">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-150">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-151">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-151">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-152">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-152">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-153">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-153">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-154">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-154">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-155">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-155">The requested sync group resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-156">同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-156">Updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-158">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-159">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-160">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-160">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-161">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-161">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-162">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-162">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-163">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-163">The requested sync group resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-165">同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-165">Updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelSync">
      <MemberSignature Language="C#" Value="public static void CancelSync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CancelSync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CancelSync (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member CancelSync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSync (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-167">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-168">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-169">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-169">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-170">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-170">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-171">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-171">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-172">同期グループの同期をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-172">Cancels a sync group synchronization.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelSyncAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelSyncAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelSyncAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSyncAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelSyncAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CancelSyncAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;CancelSyncAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-174">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-175">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-176">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-176">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-177">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-177">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-178">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-178">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-180">同期グループの同期をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-180">Cancels a sync group synchronization.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup CreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup CreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-182">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-182">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-183">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-183">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-184">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-184">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-185">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-185">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-186">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-186">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-187">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-187">The requested sync group resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-188">作成するか、同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-188">Creates or updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-190">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-190">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-191">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-191">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-192">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-192">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-193">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-193">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-194">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-194">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-195">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-195">The requested sync group resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-197">作成するか、同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-197">Creates or updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-199">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-199">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-200">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-200">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-201">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-201">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-202">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-202">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-203">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-203">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-204">同期グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-204">Deletes a sync group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-205">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-206">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-206">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-207">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-207">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-208">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-208">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-209">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-209">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-210">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-210">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-212">同期グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-212">Deletes a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup Get (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup Get(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-214">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-214">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-215">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-215">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-216">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-216">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-217">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-217">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-218">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-218">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-219">同期グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-219">Gets a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; GetAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; GetAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-221">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-221">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-222">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-222">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-223">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-223">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-224">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-224">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-225">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-225">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-227">同期グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-227">Gets a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String) As IPage(Of SyncGroup)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-229">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-229">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-230">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-230">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-231">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-231">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-232">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-232">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-233">リストは、ハブ データベースの下のグループを同期します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-233">Lists sync groups under a hub database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-234">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-235">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-235">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-236">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-236">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-237">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-237">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-238">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-238">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-239">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-240">リストは、ハブ データベースの下のグループを同期します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-240">Lists sync groups under a hub database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabaseNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; ListByDatabaseNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabaseNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncGroup)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-241">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-241">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-242">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-242">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-243">リストは、ハブ データベースの下のグループを同期します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-243">Lists sync groups under a hub database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; ListByDatabaseNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListByDatabaseNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-244">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-244">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-245">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-245">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-246">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-247">リストは、ハブ データベースの下のグループを同期します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-247">Lists sync groups under a hub database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemas">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemas (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemas(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemas(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHubSchemas (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemas : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemas (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-248">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-249">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-249">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-250">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-250">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-251">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-251">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-252">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-252">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-253">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-253">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-254">ハブ データベース スキーマのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-254">Gets a collection of hub database schemas.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemasAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListHubSchemasAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-256">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-256">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-257">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-257">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-258">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-258">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-259">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-259">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-260">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-260">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-261">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-261">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-262">ハブ データベース スキーマのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-262">Gets a collection of hub database schemas.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemasNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListHubSchemasNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHubSchemasNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemasNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-263">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-263">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-264">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-264">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-265">ハブ データベース スキーマのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-265">Gets a collection of hub database schemas.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListHubSchemasNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHubSchemasNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListHubSchemasNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListHubSchemasNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-266">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-266">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-267">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-267">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-268">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-268">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-269">ハブ データベース スキーマのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-269">Gets a collection of hub database schemas.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogs (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogs(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogs(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLogs (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, startTime As String, endTime As String, type As String, Optional continuationToken As String = null) As IPage(Of SyncGroupLogProperties)" />
      <MemberSignature Language="F#" Value="static member ListLogs : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogs (operations, resourceGroupName, serverName, databaseName, syncGroupName, startTime, endTime, type, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-270">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-270">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-271">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-271">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-272">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-272">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-273">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-273">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-274">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-274">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-275">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-275">The name of the sync group.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="a1b1a-276">この時点以降後に生成されたログを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-276">Get logs generated after this time.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="a1b1a-277">この時刻より前に生成されたログを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-277">Get logs generated before this time.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="a1b1a-278">取得するログの種類。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-278">The types of logs to retrieve.</span></span> <span data-ttu-id="a1b1a-279">使用可能な値が含まれます: 'すべて'、'Error'、'警告'、'成功'</span><span class="sxs-lookup"><span data-stu-id="a1b1a-279">Possible values include: 'All', 'Error', 'Warning', 'Success'</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="a1b1a-280">この操作の継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-280">The continuation token for this operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-281">同期グループのログのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-281">Gets a collection of sync group logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLogsAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, startTime, endTime, type, continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListLogsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-282">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-282">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-283">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-283">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-284">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-284">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-285">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-285">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-286">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-286">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-287">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-287">The name of the sync group.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="a1b1a-288">この時点以降後に生成されたログを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-288">Get logs generated after this time.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="a1b1a-289">この時刻より前に生成されたログを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-289">Get logs generated before this time.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="a1b1a-290">取得するログの種類。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-290">The types of logs to retrieve.</span></span> <span data-ttu-id="a1b1a-291">使用可能な値が含まれます: 'すべて'、'Error'、'警告'、'成功'</span><span class="sxs-lookup"><span data-stu-id="a1b1a-291">Possible values include: 'All', 'Error', 'Warning', 'Success'</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="a1b1a-292">この操作の継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-292">The continuation token for this operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-293">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-293">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-294">同期グループのログのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-294">Gets a collection of sync group logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogsNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt; ListLogsNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLogsNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncGroupLogProperties)" />
      <MemberSignature Language="F#" Value="static member ListLogsNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-295">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-295">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-296">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-296">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-297">同期グループのログのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-297">Gets a collection of sync group logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt; ListLogsNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLogsNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListLogsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListLogsNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-298">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-298">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-299">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-299">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-300">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-300">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-301">同期グループのログのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-301">Gets a collection of sync group logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIds (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIds(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIds(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSyncDatabaseIds (operations As ISyncGroupsOperations, locationName As String) As IPage(Of SyncDatabaseIdProperties)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIds : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIds (operations, locationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-302">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-302">The operations group for this extension method.</span></span>
            </param>
        <param name="locationName">
            <span data-ttu-id="a1b1a-303">リソースがある領域の名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-303">The name of the region where the resource is located.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-304">データベースの id 同期のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-304">Gets a collection of sync database ids.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string locationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIdsAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsAsync (operations, locationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListSyncDatabaseIdsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-305">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-305">The operations group for this extension method.</span></span>
            </param>
        <param name="locationName">
            <span data-ttu-id="a1b1a-306">リソースがある領域の名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-306">The name of the region where the resource is located.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-307">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-308">データベースの id 同期のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-308">Gets a collection of sync database ids.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIdsNext (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt; ListSyncDatabaseIdsNext(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNext(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSyncDatabaseIdsNext (operations As ISyncGroupsOperations, nextPageLink As String) As IPage(Of SyncDatabaseIdProperties)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIdsNext : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-309">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-309">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-310">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-310">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-311">データベースの id 同期のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-311">Gets a collection of sync database ids.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsNextAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt; ListSyncDatabaseIdsNextAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNextAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSyncDatabaseIdsNextAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.ListSyncDatabaseIdsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;ListSyncDatabaseIdsNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-312">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-312">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1b1a-313">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-313">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-314">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-315">データベースの id 同期のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-315">Gets a collection of sync database ids.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshHubSchema">
      <MemberSignature Language="C#" Value="public static void RefreshHubSchema (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RefreshHubSchema(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchema(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RefreshHubSchema (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member RefreshHubSchema : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-316">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-316">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-317">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-317">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-318">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-318">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-319">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-319">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-320">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-320">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-321">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-321">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-322">ハブ データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-322">Refreshes a hub database schema.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshHubSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RefreshHubSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RefreshHubSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchemaAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshHubSchemaAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.RefreshHubSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;RefreshHubSchemaAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-323">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-323">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-324">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-324">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-325">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-325">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-326">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-326">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-327">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-327">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-328">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-328">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-329">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-329">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-330">ハブ データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-330">Refreshes a hub database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerSync">
      <MemberSignature Language="C#" Value="public static void TriggerSync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void TriggerSync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub TriggerSync (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String)" />
      <MemberSignature Language="F#" Value="static member TriggerSync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSync (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-331">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-331">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-332">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-332">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-333">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-333">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-334">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-334">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-335">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-335">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-336">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-336">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-337">同期グループの同期をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-337">Triggers a sync group synchronization.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerSyncAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerSyncAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerSyncAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSyncAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerSyncAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.TriggerSyncAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;TriggerSyncAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-338">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-338">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-339">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-339">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-340">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-340">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-341">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-341">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-342">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-342">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-343">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-343">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-344">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-345">同期グループの同期をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-345">Triggers a sync group synchronization.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncGroup Update (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncGroup Update(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Update(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ISyncGroupsOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, parameters As SyncGroup) As SyncGroup" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.Update (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-346">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-346">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-347">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-347">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-348">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-348">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-349">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-349">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-350">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-350">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-351">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-351">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-352">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-352">The requested sync group resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-353">同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-353">Updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.ISyncGroupsOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.ISyncGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.ISyncGroupsOperations * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;" Usage="Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncGroupsOperationsExtensions/&lt;UpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1b1a-354">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-354">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1b1a-355">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-355">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a1b1a-356">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-356">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a1b1a-357">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-357">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a1b1a-358">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-358">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="a1b1a-359">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-359">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1b1a-360">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-360">The requested sync group resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1b1a-361">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-361">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1b1a-362">同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1b1a-362">Updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>