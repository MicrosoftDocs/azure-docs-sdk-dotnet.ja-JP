<Type Name="ServersOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServersOperationsExtensions = class" />
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
            <span data-ttu-id="7ce19-101">ServersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7ce19-101">Extension methods for ServersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As Server) As Server" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-105">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-106">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-106">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-107">作成するか、サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-107">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-111">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-111">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-112">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-112">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-114">作成するか、サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-114">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IServersOperations, resourceGroupName As String, serverName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-116">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-118">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-118">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-119">サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-119">Deletes a server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-121">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-122">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-123">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-123">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-125">サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-125">Deletes a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server BeginUpdate (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server BeginUpdate(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As ServerUpdate) As Server" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-127">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-127">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-128">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-129">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-129">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-130">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-130">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-131">サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-131">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-135">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-135">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-136">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-136">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-138">サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-138">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse CheckNameAvailability (this Microsoft.Azure.Management.Sql.IServersOperations operations, Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse CheckNameAvailability(class Microsoft.Azure.Management.Sql.IServersOperations operations, class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Sql.IServersOperations,Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IServersOperations, parameters As CheckNameAvailabilityRequest) As CheckNameAvailabilityResponse" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Sql.IServersOperations * Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest -&gt; Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-139">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-140">名前の可用性を要求するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-140">The parameters to request for name availability.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-141">指定した名前でリソースを作成できるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-141">Determines whether a resource can be created with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Sql.IServersOperations,Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Sql.IServersOperations * Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-142">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-143">名前の可用性を要求するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-143">The parameters to request for name availability.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-145">指定した名前でリソースを作成できるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-145">Determines whether a resource can be created with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As Server) As Server" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-147">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-147">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-148">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-148">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-149">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-149">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-150">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-150">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-151">作成するか、サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-151">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-153">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-153">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-154">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-154">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-155">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-155">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-156">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-156">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-158">作成するか、サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-158">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IServersOperations, resourceGroupName As String, serverName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Delete (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-160">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-160">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-161">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-161">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-162">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-162">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-163">サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-163">Deletes a server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-165">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-166">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-167">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-167">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-169">サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-169">Deletes a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server Get (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server Get(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServersOperations, resourceGroupName As String, serverName As String) As Server" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServersOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Get (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-171">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-171">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-172">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-172">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-173">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-173">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-174">サーバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-174">Gets a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-176">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-177">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-178">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-178">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-180">サーバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-180">Gets a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; List (this Microsoft.Azure.Management.Sql.IServersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; List(class Microsoft.Azure.Management.Sql.IServersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.List(Microsoft.Azure.Management.Sql.IServersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IServersOperations) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Sql.IServersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-181">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-182">サブスクリプション内のすべてのサーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-182">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Sql.IServersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-183">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-185">サブスクリプション内のすべてのサーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-185">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroup (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroup(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Sql.IServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IServersOperations, resourceGroupName As String) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Sql.IServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-187">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-187">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-188">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-188">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-189">リソース グループで、サーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-189">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-191">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-191">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-192">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-192">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-194">リソース グループで、サーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-194">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Sql.IServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IServersOperations, nextPageLink As String) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Sql.IServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ce19-196">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ce19-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-197">リソース グループで、サーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-197">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ce19-199">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ce19-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-201">リソース グループで、サーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-201">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; ListNext (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; ListNext(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNext(Microsoft.Azure.Management.Sql.IServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IServersOperations, nextPageLink As String) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Sql.IServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-202">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ce19-203">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ce19-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-204">サブスクリプション内のすべてのサーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-204">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ce19-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ce19-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-208">サブスクリプション内のすべてのサーバーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-208">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server Update (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server Update(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Update(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As ServerUpdate) As Server" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Update (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-210">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-210">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-211">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-211">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-212">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-212">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-213">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-213">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-214">サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-214">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;UpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ce19-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ce19-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ce19-216">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-216">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="7ce19-217">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="7ce19-217">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="7ce19-218">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ce19-218">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7ce19-219">要求されたリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="7ce19-219">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ce19-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ce19-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ce19-221">サーバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ce19-221">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>