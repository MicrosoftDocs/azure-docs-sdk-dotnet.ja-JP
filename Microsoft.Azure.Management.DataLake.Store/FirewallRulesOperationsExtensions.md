<Type Name="FirewallRulesOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FirewallRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FirewallRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FirewallRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FirewallRulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fe01a-101">FirewallRulesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="fe01a-101">Extension methods for FirewallRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String, parameters As FirewallRule) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, firewallRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-103">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-103">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-104">Data Lake Store アカウントを追加または置き換えるファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-104">The name of the Data Lake Store account to add or replace the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-105">作成または更新するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-105">The name of the firewall rule to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe01a-106">ファイアウォール規則を作成または指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fe01a-106">Parameters supplied to create or update the firewall rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-107">作成または指定されたファイアウォール規則を更新します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-107">Creates or updates the specified firewall rule.</span></span> <span data-ttu-id="fe01a-108">更新中に、この新しいファイアウォール ルールで指定した名前のファイアウォール ルールが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="fe01a-108">During update, the firewall rule with the specified name will be replaced with this new firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-110">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-110">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-111">Data Lake Store アカウントを追加または置き換えるファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-111">The name of the Data Lake Store account to add or replace the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-112">作成または更新するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-112">The name of the firewall rule to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe01a-113">ファイアウォール規則を作成または指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fe01a-113">Parameters supplied to create or update the firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe01a-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe01a-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-115">作成または指定されたファイアウォール規則を更新します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-115">Creates or updates the specified firewall rule.</span></span> <span data-ttu-id="fe01a-116">更新中に、この新しいファイアウォール ルールで指定した名前のファイアウォール ルールが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="fe01a-116">During update, the firewall rule with the specified name will be replaced with this new firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Delete (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-118">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-118">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-119">ファイアウォール規則を削除する Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-119">The name of the Data Lake Store account from which to delete the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-120">削除するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-120">The name of the firewall rule to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-121">指定された Data Lake Store アカウントから指定されたファイアウォール ルールを削除します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-121">Deletes the specified firewall rule from the specified Data Lake Store account</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-123">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-123">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-124">ファイアウォール規則を削除する Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-124">The name of the Data Lake Store account from which to delete the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-125">削除するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-125">The name of the firewall rule to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe01a-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe01a-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-127">指定された Data Lake Store アカウントから指定されたファイアウォール ルールを削除します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-127">Deletes the specified firewall rule from the specified Data Lake Store account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Get (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Get(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Get (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-129">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-129">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-130">ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-130">The name of the Data Lake Store account from which to get the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-131">取得するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-131">The name of the firewall rule to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-132">指定された Data Lake Store のファイアウォール ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-132">Gets the specified Data Lake Store firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-134">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-134">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-135">ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-135">The name of the Data Lake Store account from which to get the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-136">取得するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-136">The name of the firewall rule to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe01a-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe01a-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-138">指定された Data Lake Store のファイアウォール ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-138">Gets the specified Data Lake Store firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String) As IPage(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-140">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-140">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-141">ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-141">The name of the Data Lake Store account from which to get the firewall rules.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-142">指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-142">Lists the Data Lake Store firewall rules within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-144">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-144">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-145">ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-145">The name of the Data Lake Store account from which to get the firewall rules.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe01a-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe01a-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-147">指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-147">Lists the Data Lake Store firewall rules within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IFirewallRulesOperations, nextPageLink As String) As IPage(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-148">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fe01a-149">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fe01a-149">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-150">指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-150">Lists the Data Lake Store firewall rules within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-151">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fe01a-152">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fe01a-152">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe01a-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe01a-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-154">指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-154">Lists the Data Lake Store firewall rules within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Update (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Update(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String, Optional parameters As UpdateFirewallRuleParameters = null) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Update (operations, resourceGroupName, accountName, firewallRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-156">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-156">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-157">ファイアウォール ルールを更新するために、Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-157">The name of the Data Lake Store account to which to update the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-158">更新するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-158">The name of the firewall rule to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe01a-159">ファイアウォール ルールの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-159">Parameters supplied to update the firewall rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-160">指定されたファイアウォール規則を更新します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-160">Updates the specified firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe01a-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe01a-162">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-162">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="fe01a-163">ファイアウォール ルールを更新するために、Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-163">The name of the Data Lake Store account to which to update the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="fe01a-164">更新するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="fe01a-164">The name of the firewall rule to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe01a-165">ファイアウォール ルールの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fe01a-165">Parameters supplied to update the firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe01a-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe01a-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe01a-167">指定されたファイアウォール規則を更新します。</span><span class="sxs-lookup"><span data-stu-id="fe01a-167">Updates the specified firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>