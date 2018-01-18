<Type Name="DatabasesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabasesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabasesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabasesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabasesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="778a2-101">DatabasesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="778a2-101">Extension methods for DatabasesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-105">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-105">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-106">処理される Azure SQL データベースの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="778a2-106">The name of the Azure SQL database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="778a2-107">作成またはデータベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="778a2-107">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-109">新しい Azure SQL データベースを作成または既存の Azure SQL データベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="778a2-109">Creates a new Azure SQL database or updates an existing Azure SQL database.</span></span>
            <span data-ttu-id="778a2-110">場所は、要求本文に必要なプロパティと、SQL server の場所と同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="778a2-110">Location is a required property in the request body, and it must be the same as the location of the SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverReplicationLinkAllowDataLossAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverReplicationLinkAllowDataLossAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAllowDataLossAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverReplicationLinkAllowDataLossAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginFailoverReplicationLinkAllowDataLossAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-114">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-114">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-115">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-115">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="778a2-116">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="778a2-116">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-118">強制フェールオーバー データの損失になる可能性があります指定された ID と Azure SQL データベース レプリケーション リンクを実行します。</span><span class="sxs-lookup"><span data-stu-id="778a2-118">Force failover the Azure SQL database replication link with the given ID which may result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginFailoverReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginFailoverReplicationLinkAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-120">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-120">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-121">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-121">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-122">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-122">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-123">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-123">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="778a2-124">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="778a2-124">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-126">その ID を持つフェールオーバー Azure SQL データベース レプリケーション リンク</span><span class="sxs-lookup"><span data-stu-id="778a2-126">Failover the Azure SQL database replication link with the given ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPauseDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPauseDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPauseDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginPauseDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPauseDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginPauseDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginPauseDataWarehouseAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-128">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-128">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-129">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-129">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-130">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-130">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-131">一時停止する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-131">The name of the Azure SQL Data Warehouse database to pause.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-133">Azure SQL Data Warehouse データベースを一時停止します。</span><span class="sxs-lookup"><span data-stu-id="778a2-133">Pause an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginResumeDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginResumeDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginResumeDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.BeginResumeDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;BeginResumeDataWarehouseAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-135">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-136">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-137">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-137">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-138">再開する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-138">The name of the Azure SQL Data Warehouse database to resume.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-140">Azure SQL Data Warehouse データベースを再開します。</span><span class="sxs-lookup"><span data-stu-id="778a2-140">Resume an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-142">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-142">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-143">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-143">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-144">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-144">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-145">処理される Azure SQL データベースの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="778a2-145">The name of the Azure SQL database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="778a2-146">作成またはデータベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="778a2-146">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-148">新しい Azure SQL データベースを作成または既存の Azure SQL データベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="778a2-148">Creates a new Azure SQL database or updates an existing Azure SQL database.</span></span>
            <span data-ttu-id="778a2-149">場所は、要求本文に必要なプロパティと、SQL server の場所と同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="778a2-149">Location is a required property in the request body, and it must be the same as the location of the SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateTransparentDataEncryptionConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; CreateOrUpdateTransparentDataEncryptionConfigurationAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; CreateOrUpdateTransparentDataEncryptionConfigurationAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateTransparentDataEncryptionConfigurationAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateTransparentDataEncryptionConfigurationAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.CreateOrUpdateTransparentDataEncryptionConfigurationAsync (operations, resourceGroupName, serverName, databaseName, status, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;CreateOrUpdateTransparentDataEncryptionConfigurationAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-151">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-151">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-152">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-152">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-153">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-153">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-154">透過的なデータ暗号化を適用するための設定、Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-154">The name of the Azure SQL database for which setting the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="status">
            <span data-ttu-id="778a2-155">Azure SQL データベース透過的なデータ暗号化の状態です。</span><span class="sxs-lookup"><span data-stu-id="778a2-155">The status of the Azure SQL Database Transparent Data Encryption.</span></span> <span data-ttu-id="778a2-156">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="778a2-156">Possible values include: 'Enabled', 'Disabled'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-158">作成するか、Azure SQL データベース透過的なデータ暗号化操作を更新します。</span><span class="sxs-lookup"><span data-stu-id="778a2-158">Creates or updates an Azure SQL Database Transparent Data Encryption Operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-160">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-160">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-161">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-161">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-162">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-162">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-163">削除する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-163">The name of the Azure SQL database to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-165">Azure SQL データベースを削除します。</span><span class="sxs-lookup"><span data-stu-id="778a2-165">Deletes an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.DeleteReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;DeleteReplicationLinkAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-167">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-168">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-169">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-169">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-170">削除するレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-170">The name of the Azure SQL database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="778a2-171">削除するレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="778a2-171">The ID of the replication link to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-173">指定された ID と Azure SQL データベース レプリケーション リンクを削除します</span><span class="sxs-lookup"><span data-stu-id="778a2-173">Deletes the Azure SQL database replication link with the given ID.</span></span> <span data-ttu-id="778a2-174">フェールオーバー中には実行できません。</span><span class="sxs-lookup"><span data-stu-id="778a2-174">Cannot be done during failover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverReplicationLinkAllowDataLossAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverReplicationLinkAllowDataLossAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAllowDataLossAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverReplicationLinkAllowDataLossAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;FailoverReplicationLinkAllowDataLossAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-176">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-177">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-178">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-178">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-179">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-179">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="778a2-180">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="778a2-180">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-182">強制フェールオーバー データの損失になる可能性があります指定された ID と Azure SQL データベース レプリケーション リンクを実行します。</span><span class="sxs-lookup"><span data-stu-id="778a2-182">Force failover the Azure SQL database replication link with the given ID which may result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.FailoverReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;FailoverReplicationLinkAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-184">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-184">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-185">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-185">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-186">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-186">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-187">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-187">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="778a2-188">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="778a2-188">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-190">その ID を持つフェールオーバー Azure SQL データベース レプリケーション リンク</span><span class="sxs-lookup"><span data-stu-id="778a2-190">Failover the Azure SQL database replication link with the given ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-192">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-192">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-193">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-193">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-194">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-194">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-195">取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-195">The name of the Azure SQL database to be retrieved.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="778a2-196">コンマ区切りの応答で展開する子オブジェクトの一覧です。</span><span class="sxs-lookup"><span data-stu-id="778a2-196">The comma separated list of child objects to expand in the response.</span></span>
            <span data-ttu-id="778a2-197">使用可能なプロパティ: serviceTierAdvisors、upgradeHint、transparentDataEncryption です。</span><span class="sxs-lookup"><span data-stu-id="778a2-197">Possible properties: serviceTierAdvisors, upgradeHint, transparentDataEncryption.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-199">Azure SQL データベースに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="778a2-199">Gets information about an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReplicationLinkAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt; GetReplicationLinkAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt; GetReplicationLinkAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetReplicationLinkAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetReplicationLinkAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetReplicationLinkAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetReplicationLinkAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-200">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-201">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-201">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-202">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-202">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-203">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-203">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-204">リンクを取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-204">The name of the Azure SQL database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="778a2-205">レプリケーション リンク ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="778a2-205">The replication link ID to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-207">Azure SQL データベース レプリケーション リンクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="778a2-207">Gets information about an Azure SQL database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTierAdvisorAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; GetServiceTierAdvisorAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; GetServiceTierAdvisorAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetServiceTierAdvisorAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetServiceTierAdvisorAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetServiceTierAdvisorAsync (operations, resourceGroupName, serverName, databaseName, serviceTierAdvisorName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetServiceTierAdvisorAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-209">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-209">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-210">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-210">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-211">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-211">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-212">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-212">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="778a2-213">サービス層アドバイザーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-213">The name of service tier advisor.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-214">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-215">サービス層アドバイザーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="778a2-215">Gets information about a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransparentDataEncryptionConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; GetTransparentDataEncryptionConfigurationAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; GetTransparentDataEncryptionConfigurationAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetTransparentDataEncryptionConfigurationAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTransparentDataEncryptionConfigurationAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.GetTransparentDataEncryptionConfigurationAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;GetTransparentDataEncryptionConfigurationAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-217">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-217">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-218">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-218">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-219">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-219">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-220">透過的なデータ暗号化を適用する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-220">The name of the Azure SQL database for which the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-222">Azure SQL データベースの透過的なデータ暗号化応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="778a2-222">Gets an Azure SQL Database Transparent Data Encryption Response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListByServerAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-224">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-224">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-225">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-225">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-226">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-226">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-228">Azure SQL データベースに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="778a2-228">Returns information about an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListReplicationLinksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; ListReplicationLinksAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; ListReplicationLinksAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListReplicationLinksAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListReplicationLinksAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListReplicationLinksAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListReplicationLinksAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-230">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-230">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-231">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-231">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-232">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-232">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-233">リンクを取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-233">The name of the Azure SQL database to retrieve links for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-235">Azure SQL データベース レプリケーション リンクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="778a2-235">Gets information about Azure SQL database replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRestorePointsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt; ListRestorePointsAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt; ListRestorePointsAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListRestorePointsAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRestorePointsAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListRestorePointsAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListRestorePointsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-237">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-237">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-238">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-238">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-239">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-239">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-240">使用可能な取得する対象の Azure SQL データベースの名前は、ポイントを復元します。</span><span class="sxs-lookup"><span data-stu-id="778a2-240">The name of the Azure SQL database from which to retrieve available restore points.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-241">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-242">Azure SQL データベースの一覧を返しますでは、ポイントを復元します。</span><span class="sxs-lookup"><span data-stu-id="778a2-242">Returns a list of Azure SQL database restore points.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceTierAdvisorsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; ListServiceTierAdvisorsAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; ListServiceTierAdvisorsAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListServiceTierAdvisorsAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceTierAdvisorsAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListServiceTierAdvisorsAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListServiceTierAdvisorsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-244">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-244">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-245">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-245">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-246">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-246">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-247">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-247">The name of database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-248">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-248">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-249">指定したデータベースのサービス層アドバイザーに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="778a2-249">Returns information about service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTransparentDataEncryptionActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt; ListTransparentDataEncryptionActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt; ListTransparentDataEncryptionActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListTransparentDataEncryptionActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTransparentDataEncryptionActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListTransparentDataEncryptionActivityAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListTransparentDataEncryptionActivityAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-250">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-250">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-251">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-251">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-252">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-252">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-253">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-253">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-254">透過的なデータ暗号化を適用する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-254">The name of the Azure SQL database for which the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-256">Azure SQL データベース透過的なデータの暗号化活動応答を返します。</span><span class="sxs-lookup"><span data-stu-id="778a2-256">Returns an Azure SQL Database Transparent Data Encryption Activity Response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ListUsagesAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-257">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-257">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-258">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-258">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-259">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-259">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-260">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-260">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-261">Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-261">The name of the Azure SQL database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-262">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-263">Azure SQL データベースの使用状況に関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="778a2-263">Returns information about Azure SQL database usages.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PauseDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PauseDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PauseDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.PauseDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PauseDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.PauseDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;PauseDataWarehouseAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-264">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-264">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-265">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-265">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-266">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-266">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-267">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-267">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-268">一時停止する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-268">The name of the Azure SQL Data Warehouse database to pause.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-270">Azure SQL Data Warehouse データベースを一時停止します。</span><span class="sxs-lookup"><span data-stu-id="778a2-270">Pause an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeDataWarehouseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResumeDataWarehouseAsync (this Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResumeDataWarehouseAsync(class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ResumeDataWarehouseAsync(Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeDataWarehouseAsync : Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions.ResumeDataWarehouseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.DatabasesOperationsExtensions/&lt;ResumeDataWarehouseAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="778a2-271">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="778a2-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="778a2-272">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-272">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="778a2-273">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="778a2-273">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="778a2-274">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-274">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="778a2-275">再開する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="778a2-275">The name of the Azure SQL Data Warehouse database to resume.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="778a2-276">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="778a2-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="778a2-277">Azure SQL Data Warehouse データベースを再開します。</span><span class="sxs-lookup"><span data-stu-id="778a2-277">Resume an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>