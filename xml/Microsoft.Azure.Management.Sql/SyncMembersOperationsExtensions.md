<Type Name="SyncMembersOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SyncMembersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SyncMembersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SyncMembersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SyncMembersOperationsExtensions = class" />
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
            <span data-ttu-id="d22f8-101">SyncMembersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="d22f8-101">Extension methods for SyncMembersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-106">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-106">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-107">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-107">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-108">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-108">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-109">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-109">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-110">作成するか、同期のメンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-110">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-114">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-114">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-115">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-115">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-116">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-116">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-117">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-117">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-118">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-118">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-120">作成するか、同期のメンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-120">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-122">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-123">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-124">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-124">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-125">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-125">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-126">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-126">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-127">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-127">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-128">同期のメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-128">Deletes a sync member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-130">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-130">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-131">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-131">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-132">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-132">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-133">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-133">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-134">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-134">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-135">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-135">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-137">同期のメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-137">Deletes a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshMemberSchema">
      <MemberSignature Language="C#" Value="public static void BeginRefreshMemberSchema (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginRefreshMemberSchema(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchema(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginRefreshMemberSchema (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshMemberSchema : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-139">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-139">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-140">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-141">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-141">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-142">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-142">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-143">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-143">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-144">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-144">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-145">同期メンバー データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-145">Refreshes a sync member database schema.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshMemberSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginRefreshMemberSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginRefreshMemberSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchemaAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRefreshMemberSchemaAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginRefreshMemberSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginRefreshMemberSchemaAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-147">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-147">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-148">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-148">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-149">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-149">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-150">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-150">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-151">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-151">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-152">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-152">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-154">同期メンバー データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-154">Refreshes a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember BeginUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember BeginUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-156">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-156">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-157">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-157">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-158">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-158">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-159">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-159">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-160">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-160">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-161">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-161">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-162">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-162">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-163">既存の同期メンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-163">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-165">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-166">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-167">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-167">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-168">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-168">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-169">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-169">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-170">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-170">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-171">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-171">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-173">既存の同期メンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-173">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember CreateOrUpdate (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember CreateOrUpdate(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-175">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-175">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-176">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-176">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-177">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-177">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-178">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-178">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-179">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-179">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-180">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-180">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-181">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-181">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-182">作成するか、同期のメンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-182">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-184">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-184">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-185">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-185">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-186">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-186">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-187">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-187">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-188">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-188">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-189">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-189">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-190">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-190">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-192">作成するか、同期のメンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-192">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Delete (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-194">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-194">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-195">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-195">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-196">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-196">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-197">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-197">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-198">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-198">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-199">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-199">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-200">同期のメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-200">Deletes a sync member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-202">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-202">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-203">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-203">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-204">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-204">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-205">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-205">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-206">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-206">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-207">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-207">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-209">同期のメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-209">Deletes a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember Get (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember Get(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String) As SyncMember" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-211">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-211">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-212">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-212">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-213">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-213">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-214">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-214">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-215">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-215">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-216">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-216">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-217">同期のメンバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-217">Gets a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; GetAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; GetAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-219">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-219">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-220">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-220">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-221">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-221">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-222">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-222">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-223">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-223">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-224">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-224">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-226">同期のメンバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-226">Gets a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroup (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroup(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroup(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySyncGroup (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String) As IPage(Of SyncMember)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroup : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroup (operations, resourceGroupName, serverName, databaseName, syncGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-227">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-228">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-228">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-229">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-229">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-230">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-230">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-231">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-231">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-232">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d22f8-232">The name of the sync group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-233">リストは、指定された同期グループ内のメンバーを同期します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-233">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListBySyncGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-234">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-235">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-235">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-236">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-236">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-237">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-237">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-238">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-238">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-239">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d22f8-239">The name of the sync group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-241">リストは、指定された同期グループ内のメンバーを同期します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-241">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroupNext (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; ListBySyncGroupNext(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNext(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySyncGroupNext (operations As ISyncMembersOperations, nextPageLink As String) As IPage(Of SyncMember)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupNext : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-242">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d22f8-243">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d22f8-243">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-244">リストは、指定された同期グループ内のメンバーを同期します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-244">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupNextAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; ListBySyncGroupNextAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNextAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySyncGroupNextAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListBySyncGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListBySyncGroupNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-245">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-245">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d22f8-246">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d22f8-246">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-247">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-248">リストは、指定された同期グループ内のメンバーを同期します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-248">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemas">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemas (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemas(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemas(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMemberSchemas (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemas : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemas (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-250">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-250">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-251">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-251">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-252">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-252">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-253">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-253">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-254">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-254">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-255">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-255">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-256">同期メンバー データベース スキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-256">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListMemberSchemasAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-257">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-257">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-258">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-258">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-259">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-259">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-260">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-260">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-261">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-261">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-262">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-262">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-263">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-263">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-264">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-265">同期メンバー データベース スキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-265">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemasNext (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt; ListMemberSchemasNext(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNext(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMemberSchemasNext (operations As ISyncMembersOperations, nextPageLink As String) As IPage(Of SyncFullSchemaProperties)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasNext : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-266">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-266">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d22f8-267">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d22f8-267">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-268">同期メンバー データベース スキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-268">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasNextAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt; ListMemberSchemasNextAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNextAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMemberSchemasNextAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.ListMemberSchemasNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;ListMemberSchemasNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-269">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-269">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d22f8-270">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d22f8-270">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-272">同期メンバー データベース スキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-272">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshMemberSchema">
      <MemberSignature Language="C#" Value="public static void RefreshMemberSchema (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RefreshMemberSchema(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchema(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RefreshMemberSchema (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String)" />
      <MemberSignature Language="F#" Value="static member RefreshMemberSchema : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchema (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-274">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-274">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-275">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-275">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-276">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-276">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-277">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-277">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-278">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-278">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-279">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-279">The name of the sync member.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-280">同期メンバー データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-280">Refreshes a sync member database schema.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshMemberSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RefreshMemberSchemaAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RefreshMemberSchemaAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchemaAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshMemberSchemaAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.RefreshMemberSchemaAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;RefreshMemberSchemaAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-281">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-281">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-282">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-282">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-283">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-283">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-284">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-284">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-285">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-285">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-286">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-286">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-287">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-287">The name of the sync member.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-288">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-289">同期メンバー データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-289">Refreshes a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.SyncMember Update (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.SyncMember Update(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Update(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ISyncMembersOperations, resourceGroupName As String, serverName As String, databaseName As String, syncGroupName As String, syncMemberName As String, parameters As SyncMember) As SyncMember" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.Update (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-290">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-290">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-291">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-291">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-292">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-292">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-293">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-293">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-294">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-294">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-295">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-295">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-296">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-296">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-297">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-297">The requested sync member resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-298">既存の同期メンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-298">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.ISyncMembersOperations operations, string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.ISyncMembersOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.ISyncMembersOperations * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;" Usage="Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.SyncMembersOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ISyncMembersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d22f8-299">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d22f8-299">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d22f8-300">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-300">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d22f8-301">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d22f8-301">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d22f8-302">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-302">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="d22f8-303">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-303">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="d22f8-304">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-304">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="d22f8-305">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d22f8-305">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d22f8-306">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="d22f8-306">The requested sync member resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d22f8-307">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d22f8-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d22f8-308">既存の同期メンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d22f8-308">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>