<Type Name="ServerDnsAliasesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServerDnsAliasesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServerDnsAliasesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServerDnsAliasesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServerDnsAliasesOperationsExtensions = class" />
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
            <span data-ttu-id="24c8a-101">ServerDnsAliasesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="24c8a-101">Extension methods for ServerDnsAliasesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Acquire">
      <MemberSignature Language="C#" Value="public static void Acquire (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Acquire(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Acquire(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Acquire (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String, parameters As ServerDnsAliasAcquisition)" />
      <MemberSignature Language="F#" Value="static member Acquire : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Acquire (operations, resourceGroupName, serverName, dnsAliasName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-105">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-105">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-106">サーバーの dns エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-106">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <summary>
            <span data-ttu-id="24c8a-107">別のサーバーからサーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-107">Acquires server DNS alias from another server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AcquireAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AcquireAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.AcquireAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AcquireAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.AcquireAsync (operations, resourceGroupName, serverName, dnsAliasName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;AcquireAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-111">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-111">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-112">サーバーの dns エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-112">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-114">別のサーバーからサーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-114">Acquires server DNS alias from another server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquire">
      <MemberSignature Language="C#" Value="public static void BeginAcquire (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginAcquire(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquire(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginAcquire (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String, parameters As ServerDnsAliasAcquisition)" />
      <MemberSignature Language="F#" Value="static member BeginAcquire : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquire (operations, resourceGroupName, serverName, dnsAliasName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-116">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-118">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-118">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-119">サーバーの dns エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-119">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <summary>
            <span data-ttu-id="24c8a-120">別のサーバーからサーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-120">Acquires server DNS alias from another server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquireAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginAcquireAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginAcquireAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquireAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginAcquireAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginAcquireAsync (operations, resourceGroupName, serverName, dnsAliasName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;BeginAcquireAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-122">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-123">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-124">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-124">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-125">サーバーの dns エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-125">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-127">別のサーバーからサーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-127">Acquires server DNS alias from another server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerDnsAlias BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String) As ServerDnsAlias" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerDnsAlias" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerDnsAlias</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-129">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-129">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-130">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-130">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-131">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-131">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-132">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-132">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-133">サーバーの dns エイリアスを作成します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-133">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-135">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-136">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-137">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-137">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-138">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-138">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-140">サーバーの dns エイリアスを作成します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-140">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-142">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-142">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-143">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-143">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-144">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-144">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-145">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-145">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-146">指定された名前が付いたエイリアスが DNS サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-146">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-148">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-148">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-149">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-149">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-150">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-150">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-151">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-151">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-153">指定された名前が付いたエイリアスが DNS サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-153">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerDnsAlias CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String) As ServerDnsAlias" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerDnsAlias" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerDnsAlias</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-155">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-155">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-156">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-156">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-157">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-157">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-158">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-158">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-159">サーバーの dns エイリアスを作成します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-159">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-161">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-161">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-162">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-162">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-163">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-163">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-164">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-164">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-166">サーバーの dns エイリアスを作成します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-166">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Delete (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-168">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-168">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-169">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-169">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-170">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-170">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-171">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-171">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-172">指定された名前が付いたエイリアスが DNS サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-172">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-174">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-175">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-176">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-176">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-177">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-177">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-179">指定された名前が付いたエイリアスが DNS サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-179">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerDnsAlias Get (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias Get(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String, dnsAliasName As String) As ServerDnsAlias" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerDnsAlias" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.Get (operations, resourceGroupName, serverName, dnsAliasName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerDnsAlias</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-181">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-181">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-182">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-182">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-183">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-183">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-184">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-184">The name of the server DNS alias.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-185">サーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-185">Gets a server DNS alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, string dnsAliasName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, dnsAliasName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-187">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-187">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-188">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-188">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-189">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-189">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="24c8a-190">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-190">The name of the server DNS alias.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-192">サーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-192">Gets a server DNS alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServer (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServer(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IServerDnsAliasesOperations, resourceGroupName As String, serverName As String) As IPage(Of ServerDnsAlias)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-194">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-194">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-195">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-195">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-196">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-196">The name of the server that the alias is pointing to.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-197">サーバーのサーバーの DNS エイリアスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-197">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;ListByServerAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="24c8a-199">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-199">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="24c8a-200">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="24c8a-200">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="24c8a-201">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="24c8a-201">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-203">サーバーのサーバーの DNS エイリアスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-203">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IServerDnsAliasesOperations, nextPageLink As String) As IPage(Of ServerDnsAlias)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-204">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="24c8a-205">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="24c8a-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-206">サーバーのサーバーの DNS エイリアスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-206">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerDnsAliasesOperationsExtensions/&lt;ListByServerNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="24c8a-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="24c8a-207">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="24c8a-208">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="24c8a-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="24c8a-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="24c8a-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="24c8a-210">サーバーのサーバーの DNS エイリアスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="24c8a-210">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>