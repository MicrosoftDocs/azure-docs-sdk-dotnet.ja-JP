<Type Name="ReplicationLinksOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ReplicationLinksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ReplicationLinksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ReplicationLinksOperationsExtensions = class" />
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
            <span data-ttu-id="fffdd-101">ReplicationLinksOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="fffdd-101">Extension methods for ReplicationLinksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginFailover">
      <MemberSignature Language="C#" Value="public static void BeginFailover (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailover(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailover(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailover (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailover : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailover (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-106">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-106">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-107">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-107">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-108">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-108">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static void BeginFailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailoverAllowDataLoss (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLoss (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-112">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-113">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-113">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-114">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-114">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-115">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-115">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="fffdd-116">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fffdd-116">This operation might result in data loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;BeginFailoverAllowDataLossAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-120">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-121">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-121">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-122">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-122">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fffdd-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fffdd-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-124">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-124">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="fffdd-125">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fffdd-125">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.BeginFailoverAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;BeginFailoverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-127">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-127">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-128">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-129">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-129">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-130">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-130">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-131">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-131">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fffdd-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fffdd-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-133">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-133">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-135">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-136">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-137">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-137">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-138">削除するレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-138">The name of the database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-139">削除するレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-139">The ID of the replication link to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-140">データベース レプリケーション リンクを削除します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-140">Deletes a database replication link.</span></span> <span data-ttu-id="fffdd-141">フェールオーバー中には実行できません。</span><span class="sxs-lookup"><span data-stu-id="fffdd-141">Cannot be done during failover.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-143">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-143">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-144">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-144">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-145">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-145">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-146">削除するレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-146">The name of the database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-147">削除するレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-147">The ID of the replication link to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fffdd-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fffdd-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-149">データベース レプリケーション リンクを削除します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-149">Deletes a database replication link.</span></span> <span data-ttu-id="fffdd-150">フェールオーバー中には実行できません。</span><span class="sxs-lookup"><span data-stu-id="fffdd-150">Cannot be done during failover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public static void Failover (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Failover(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Failover(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Failover (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member Failover : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Failover (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-152">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-153">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-154">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-154">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-155">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-155">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-156">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-156">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-157">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-157">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static void FailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void FailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub FailoverAllowDataLoss (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String)" />
      <MemberSignature Language="F#" Value="static member FailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLoss (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-159">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-160">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-161">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-161">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-162">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-162">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-163">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-163">The ID of the replication link to be failed over.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-164">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-164">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="fffdd-165">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fffdd-165">This operation might result in data loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAllowDataLossAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;FailoverAllowDataLossAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-167">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-168">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-169">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-169">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-170">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-170">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-171">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-171">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fffdd-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fffdd-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-173">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-173">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="fffdd-174">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fffdd-174">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.FailoverAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;FailoverAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-176">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-177">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-178">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-178">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-179">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-179">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-180">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="fffdd-180">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fffdd-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fffdd-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-182">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-182">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ReplicationLink Get (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ReplicationLink Get(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String, linkId As String) As ReplicationLink" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ReplicationLink" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ReplicationLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-184">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-184">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-185">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-185">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-186">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-186">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-187">リンクを取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-187">The name of the database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-188">レプリケーション リンク ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-188">The replication link ID to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-189">データベース レプリケーション リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-189">Gets a database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; GetAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; GetAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-191">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-191">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-192">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-192">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-193">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-193">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-194">リンクを取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-194">The name of the database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="fffdd-195">レプリケーション リンク ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-195">The replication link ID to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fffdd-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fffdd-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-197">データベース レプリケーション リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-197">Gets a database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IReplicationLinksOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of ReplicationLink)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-199">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-199">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-200">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-200">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-201">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-201">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-202">リンクを取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-202">The name of the database to retrieve links for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-203">データベースのレプリケーション リンクを示します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-203">Lists a database's replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IReplicationLinksOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IReplicationLinksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IReplicationLinksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ReplicationLinksOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IReplicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fffdd-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fffdd-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fffdd-205">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-205">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fffdd-206">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fffdd-206">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fffdd-207">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-207">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fffdd-208">リンクを取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fffdd-208">The name of the database to retrieve links for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fffdd-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fffdd-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fffdd-210">データベースのレプリケーション リンクを示します。</span><span class="sxs-lookup"><span data-stu-id="fffdd-210">Lists a database's replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>