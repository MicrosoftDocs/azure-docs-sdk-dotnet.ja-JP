<Type Name="IFirewallRulesOperations" FullName="Microsoft.Azure.Management.Redis.IFirewallRulesOperations">
  <TypeSignature Language="C#" Value="public interface IFirewallRulesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFirewallRulesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.IFirewallRulesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFirewallRulesOperations" />
  <TypeSignature Language="F#" Value="type IFirewallRulesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd60e-101">FirewallRulesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="dd60e-101">FirewallRulesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string cacheName, string ruleName, Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string cacheName, string ruleName, class Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IFirewallRulesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;" Usage="iFirewallRulesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, cacheName, ruleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cacheName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisFirewallRuleCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dd60e-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-102">The name of the resource group.</span></span>
            </param>
        <param name="cacheName">
            <span data-ttu-id="dd60e-103">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-103">The name of the Redis cache.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="dd60e-104">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="dd60e-104">The name of the firewall rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dd60e-105">作成または更新プログラムに渡されるパラメーターは redis のファイアウォール ルールの操作です。</span><span class="sxs-lookup"><span data-stu-id="dd60e-105">Parameters supplied to the create or update redis firewall rule operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dd60e-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd60e-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dd60e-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd60e-108">作成または redis キャッシュのファイアウォール ルールを更新</span><span class="sxs-lookup"><span data-stu-id="dd60e-108">Create or update a redis cache firewall rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dd60e-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="dd60e-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd60e-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string cacheName, string ruleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string cacheName, string ruleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IFirewallRulesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFirewallRulesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, cacheName, ruleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cacheName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dd60e-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-112">The name of the resource group.</span></span>
            </param>
        <param name="cacheName">
            <span data-ttu-id="dd60e-113">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-113">The name of the Redis cache.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="dd60e-114">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="dd60e-114">The name of the firewall rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dd60e-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd60e-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dd60e-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd60e-117">指定した redis キャッシュ内の単一のファイアウォール規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-117">Deletes a single firewall rule in a specified redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dd60e-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd60e-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string cacheName, string ruleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string cacheName, string ruleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IFirewallRulesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;" Usage="iFirewallRulesOperations.GetWithHttpMessagesAsync (resourceGroupName, cacheName, ruleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cacheName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dd60e-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-120">The name of the resource group.</span></span>
            </param>
        <param name="cacheName">
            <span data-ttu-id="dd60e-121">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-121">The name of the Redis cache.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="dd60e-122">ファイアウォール規則の名前です。</span><span class="sxs-lookup"><span data-stu-id="dd60e-122">The name of the firewall rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dd60e-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd60e-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dd60e-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd60e-125">指定した redis キャッシュ内の単一のファイアウォール ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-125">Gets a single firewall rule in a specified redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dd60e-126">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-126">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="dd60e-127">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-127">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd60e-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByRedisResourceNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt; ListByRedisResourceNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt; ListByRedisResourceNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IFirewallRulesOperations.ListByRedisResourceNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByRedisResourceNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt;" Usage="iFirewallRulesOperations.ListByRedisResourceNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="dd60e-129">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="dd60e-129">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dd60e-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd60e-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dd60e-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd60e-132">指定した redis cache のすべてのファイアウォール ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-132">Gets all firewall rules in the specified redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dd60e-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="dd60e-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd60e-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByRedisResourceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt; ListByRedisResourceWithHttpMessagesAsync (string resourceGroupName, string cacheName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt; ListByRedisResourceWithHttpMessagesAsync(string resourceGroupName, string cacheName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IFirewallRulesOperations.ListByRedisResourceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByRedisResourceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt;" Usage="iFirewallRulesOperations.ListByRedisResourceWithHttpMessagesAsync (resourceGroupName, cacheName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisFirewallRule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cacheName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dd60e-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-136">The name of the resource group.</span></span>
            </param>
        <param name="cacheName">
            <span data-ttu-id="dd60e-137">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="dd60e-137">The name of the Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dd60e-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dd60e-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dd60e-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dd60e-140">指定した redis cache のすべてのファイアウォール ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="dd60e-140">Gets all firewall rules in the specified redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dd60e-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="dd60e-142">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-142">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd60e-143">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd60e-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>