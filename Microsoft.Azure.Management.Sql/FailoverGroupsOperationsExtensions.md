<Type Name="FailoverGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FailoverGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FailoverGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FailoverGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FailoverGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="55a01-101">FailoverGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="55a01-101">Extension methods for FailoverGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroup) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-105">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-105">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-106">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-106">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-107">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-107">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-108">作成またはフェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-108">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-112">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-112">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-113">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-113">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-114">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-114">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-116">作成またはフェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-116">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-120">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-120">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-121">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-121">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-122">グループのフェールオーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="55a01-122">Deletes a failover group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-126">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-126">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-127">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-127">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-129">グループのフェールオーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="55a01-129">Deletes a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailover">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginFailover (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginFailover(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailover(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginFailover (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginFailover : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailover (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-131">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-132">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-133">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-133">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-134">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-134">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-135">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-135">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginFailoverAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginFailoverAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailoverAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginFailoverAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginFailoverAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-137">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-138">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-139">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-139">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-140">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-140">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-142">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-142">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginForceFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginForceFailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginForceFailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginForceFailoverAllowDataLoss (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginForceFailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLoss (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-144">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-145">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-146">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-146">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-147">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-147">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-148">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-148">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="55a01-149">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="55a01-149">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginForceFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginForceFailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginForceFailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginForceFailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginForceFailoverAllowDataLossAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginForceFailoverAllowDataLossAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-151">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-151">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-152">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-152">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-153">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-153">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-154">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-154">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-156">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-156">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="55a01-157">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="55a01-157">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginUpdate (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup BeginUpdate(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroupUpdate) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-159">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-160">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-161">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-161">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-162">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-162">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-163">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-163">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-164">フェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-164">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-166">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-166">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-167">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-167">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-168">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-168">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-169">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-169">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-170">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-170">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-172">フェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-172">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup CreateOrUpdate (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup CreateOrUpdate(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroup) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-174">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-175">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-176">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-176">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-177">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-177">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-178">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-178">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-179">作成またはフェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-179">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-181">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-181">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-182">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-182">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-183">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-183">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-184">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-184">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-185">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-185">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-187">作成またはフェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-187">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Delete (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-189">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-189">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-190">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-190">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-191">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-191">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-192">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-192">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-193">グループのフェールオーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="55a01-193">Deletes a failover group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-195">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-195">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-196">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-196">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-197">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-197">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-198">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-198">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-200">グループのフェールオーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="55a01-200">Deletes a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup Failover (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup Failover(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Failover(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Failover (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member Failover : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Failover (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-202">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-202">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-203">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-203">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-204">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-204">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-205">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-205">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-206">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-206">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; FailoverAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; FailoverAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.FailoverAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.FailoverAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;FailoverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-207">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-208">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-208">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-209">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-209">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-210">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-210">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-211">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-211">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-213">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-213">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLoss">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup ForceFailoverAllowDataLoss (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup ForceFailoverAllowDataLoss(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLoss(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ForceFailoverAllowDataLoss (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member ForceFailoverAllowDataLoss : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLoss (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-215">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-215">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-216">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-216">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-217">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-217">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-218">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-218">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-219">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-219">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="55a01-220">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="55a01-220">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLossAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ForceFailoverAllowDataLossAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ForceFailoverAllowDataLossAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLossAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForceFailoverAllowDataLossAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ForceFailoverAllowDataLossAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;ForceFailoverAllowDataLossAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-222">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-222">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-223">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-223">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-224">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-224">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-225">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-225">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-227">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="55a01-227">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="55a01-228">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="55a01-228">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup Get (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup Get(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Get (operations, resourceGroupName, serverName, failoverGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-230">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-230">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-231">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-231">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-232">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-232">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-233">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-233">The name of the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-234">フェールオーバー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="55a01-234">Gets a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; GetAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; GetAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, failoverGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-235">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-236">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-236">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-237">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-237">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-238">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-238">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-239">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-239">The name of the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-241">フェールオーバー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="55a01-241">Gets a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServer (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServer(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String) As IPage(Of FailoverGroup)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-243">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-243">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-244">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-244">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-245">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-245">The name of the server containing the failover group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-246">サーバーにフェールオーバー グループが表示されます。</span><span class="sxs-lookup"><span data-stu-id="55a01-246">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;ListByServerAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-248">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-248">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-249">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-249">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-250">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-250">The name of the server containing the failover group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-251">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-252">サーバーにフェールオーバー グループが表示されます。</span><span class="sxs-lookup"><span data-stu-id="55a01-252">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IFailoverGroupsOperations, nextPageLink As String) As IPage(Of FailoverGroup)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-253">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-253">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="55a01-254">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="55a01-254">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-255">サーバーにフェールオーバー グループが表示されます。</span><span class="sxs-lookup"><span data-stu-id="55a01-255">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;ListByServerNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-256">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="55a01-257">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="55a01-257">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-259">サーバーにフェールオーバー グループが表示されます。</span><span class="sxs-lookup"><span data-stu-id="55a01-259">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FailoverGroup Update (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FailoverGroup Update(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Update(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IFailoverGroupsOperations, resourceGroupName As String, serverName As String, failoverGroupName As String, parameters As FailoverGroupUpdate) As FailoverGroup" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroup" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.Update (operations, resourceGroupName, serverName, failoverGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-261">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-261">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-262">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-262">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-263">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-263">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-264">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-264">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-265">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-265">The failover group parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-266">フェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-266">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations operations, string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.IFailoverGroupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;" Usage="Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, failoverGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FailoverGroupsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55a01-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55a01-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="55a01-268">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-268">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="55a01-269">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="55a01-269">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="55a01-270">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-270">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="55a01-271">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="55a01-271">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="55a01-272">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="55a01-272">The failover group parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55a01-273">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55a01-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55a01-274">フェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="55a01-274">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>