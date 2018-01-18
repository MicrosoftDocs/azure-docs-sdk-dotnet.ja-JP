<Type Name="FirewallRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FirewallRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FirewallRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FirewallRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FirewallRulesOperationsExtensions = class" />
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
            <span data-ttu-id="77edd-101">FirewallRulesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="77edd-101">Extension methods for FirewallRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FirewallRule CreateOrUpdate (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, Microsoft.Azure.Management.Sql.Models.FirewallRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FirewallRule CreateOrUpdate(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, class Microsoft.Azure.Management.Sql.Models.FirewallRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FirewallRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IFirewallRulesOperations, resourceGroupName As String, serverName As String, firewallRuleName As String, parameters As FirewallRule) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FirewallRule -&gt; Microsoft.Azure.Management.Sql.Models.FirewallRule" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, firewallRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FirewallRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-105">The name of the server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="77edd-106">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="77edd-106">The name of the firewall rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="77edd-107">作成または更新するファイアウォール規則の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="77edd-107">The required parameters for creating or updating a firewall rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-108">ファイアウォール規則を作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="77edd-108">Creates or updates a firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, Microsoft.Azure.Management.Sql.Models.FirewallRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FirewallRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, class Microsoft.Azure.Management.Sql.Models.FirewallRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FirewallRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.FirewallRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FirewallRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-112">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-112">The name of the server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="77edd-113">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="77edd-113">The name of the firewall rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="77edd-114">作成または更新するファイアウォール規則の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="77edd-114">The required parameters for creating or updating a firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77edd-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77edd-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-116">ファイアウォール規則を作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="77edd-116">Creates or updates a firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFirewallRulesOperations, resourceGroupName As String, serverName As String, firewallRuleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.Delete (operations, resourceGroupName, serverName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-120">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-120">The name of the server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="77edd-121">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="77edd-121">The name of the firewall rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-122">ファイアウォール規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="77edd-122">Deletes a firewall rule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-126">The name of the server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="77edd-127">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="77edd-127">The name of the firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77edd-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77edd-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-129">ファイアウォール規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="77edd-129">Deletes a firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.FirewallRule Get (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.FirewallRule Get(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFirewallRulesOperations, resourceGroupName As String, serverName As String, firewallRuleName As String) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FirewallRule" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.Get (operations, resourceGroupName, serverName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-131">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-132">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-133">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-133">The name of the server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="77edd-134">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="77edd-134">The name of the firewall rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-135">ファイアウォール規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="77edd-135">Gets a firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt; GetAsync (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.FirewallRule&gt; GetAsync(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-137">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-138">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-139">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-139">The name of the server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="77edd-140">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="77edd-140">The name of the firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77edd-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77edd-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-142">ファイアウォール規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="77edd-142">Gets a firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt; ListByServer (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.FirewallRule&gt; ListByServer(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IFirewallRulesOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-144">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-145">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-146">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-146">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-147">ファイアウォール規則の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="77edd-147">Returns a list of firewall rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IFirewallRulesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IFirewallRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IFirewallRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.FirewallRulesOperationsExtensions/&lt;ListByServerAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="77edd-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="77edd-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="77edd-149">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-149">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="77edd-150">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="77edd-150">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="77edd-151">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="77edd-151">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77edd-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77edd-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77edd-153">ファイアウォール規則の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="77edd-153">Returns a list of firewall rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>