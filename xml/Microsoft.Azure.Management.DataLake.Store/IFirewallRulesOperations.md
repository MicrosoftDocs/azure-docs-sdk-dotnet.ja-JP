<Type Name="IFirewallRulesOperations" FullName="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations">
  <TypeSignature Language="C#" Value="public interface IFirewallRulesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFirewallRulesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFirewallRulesOperations" />
  <TypeSignature Language="F#" Value="type IFirewallRulesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81aa8-101">FirewallRulesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="81aa8-101">FirewallRulesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;" Usage="iFirewallRulesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, accountName, firewallRuleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="81aa8-102">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-102">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="81aa8-103">Data Lake Store アカウントを追加または置き換えるファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-103">The name of the Data Lake Store account to add or replace the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="81aa8-104">作成または更新するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-104">The name of the firewall rule to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="81aa8-105">ファイアウォール規則を作成または指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="81aa8-105">Parameters supplied to create or update the firewall rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81aa8-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81aa8-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81aa8-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81aa8-108">作成または指定されたファイアウォール規則を更新します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-108">Creates or updates the specified firewall rule.</span></span> <span data-ttu-id="81aa8-109">更新中に、この新しいファイアウォール ルールで指定した名前のファイアウォール ルールが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-109">During update, the firewall rule with the specified name will be replaced with this new firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81aa8-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="81aa8-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81aa8-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string firewallRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string firewallRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFirewallRulesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, firewallRuleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="81aa8-113">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-113">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="81aa8-114">ファイアウォール規則を削除する Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-114">The name of the Data Lake Store account from which to delete the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="81aa8-115">削除するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-115">The name of the firewall rule to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81aa8-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81aa8-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81aa8-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81aa8-118">指定された Data Lake Store アカウントから指定されたファイアウォール ルールを削除します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-118">Deletes the specified firewall rule from the specified Data Lake Store account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81aa8-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81aa8-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string firewallRuleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string firewallRuleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;" Usage="iFirewallRulesOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, firewallRuleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="81aa8-121">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-121">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="81aa8-122">ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-122">The name of the Data Lake Store account from which to get the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="81aa8-123">取得するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-123">The name of the firewall rule to retrieve.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81aa8-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81aa8-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81aa8-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81aa8-126">指定された Data Lake Store のファイアウォール ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-126">Gets the specified Data Lake Store firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81aa8-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="81aa8-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81aa8-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations.ListByAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt;" Usage="iFirewallRulesOperations.ListByAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="81aa8-130">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="81aa8-130">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81aa8-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81aa8-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81aa8-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81aa8-133">指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-133">Lists the Data Lake Store firewall rules within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81aa8-134">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-134">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="81aa8-135">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-135">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81aa8-136">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-136">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations.ListByAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt;" Usage="iFirewallRulesOperations.ListByAccountWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="81aa8-137">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-137">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="81aa8-138">ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-138">The name of the Data Lake Store account from which to get the firewall rules.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81aa8-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81aa8-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81aa8-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81aa8-141">指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-141">Lists the Data Lake Store firewall rules within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81aa8-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="81aa8-143">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-143">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81aa8-144">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;" Usage="iFirewallRulesOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, firewallRuleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="81aa8-145">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-145">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="81aa8-146">ファイアウォール ルールを更新するために、Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-146">The name of the Data Lake Store account to which to update the firewall rule.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="81aa8-147">更新するファイアウォール規則の名前。</span><span class="sxs-lookup"><span data-stu-id="81aa8-147">The name of the firewall rule to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="81aa8-148">ファイアウォール ルールの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="81aa8-148">Parameters supplied to update the firewall rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81aa8-149">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-149">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81aa8-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81aa8-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81aa8-151">指定されたファイアウォール規則を更新します。</span><span class="sxs-lookup"><span data-stu-id="81aa8-151">Updates the specified firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81aa8-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="81aa8-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81aa8-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81aa8-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>