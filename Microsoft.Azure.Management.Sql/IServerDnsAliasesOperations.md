<Type Name="IServerDnsAliasesOperations" FullName="Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations">
  <TypeSignature Language="C#" Value="public interface IServerDnsAliasesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServerDnsAliasesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServerDnsAliasesOperations" />
  <TypeSignature Language="F#" Value="type IServerDnsAliasesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="af5e0-101">ServerDnsAliasesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="af5e0-101">ServerDnsAliasesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; AcquireWithHttpMessagesAsync (string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; AcquireWithHttpMessagesAsync(string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.AcquireWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AcquireWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iServerDnsAliasesOperations.AcquireWithHttpMessagesAsync (resourceGroupName, serverName, dnsAliasName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-104">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-104">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="af5e0-105">サーバーの dns エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-105">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-108">別のサーバーからサーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-108">Acquires server DNS alias from another server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquireWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginAcquireWithHttpMessagesAsync (string resourceGroupName, string serverName, string dnsAliasName, Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginAcquireWithHttpMessagesAsync(string resourceGroupName, string serverName, string dnsAliasName, class Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.BeginAcquireWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginAcquireWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iServerDnsAliasesOperations.BeginAcquireWithHttpMessagesAsync (resourceGroupName, serverName, dnsAliasName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerDnsAliasAcquisition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-111">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-112">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-113">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-113">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="af5e0-114">サーバーの dns エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-114">The name of the server dns alias.</span></span>
            </param>
        <param name="parameters"></param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-117">別のサーバーからサーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-117">Acquires server DNS alias from another server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string dnsAliasName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string dnsAliasName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;" Usage="iServerDnsAliasesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, dnsAliasName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-120">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-120">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-121">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-121">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-122">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-122">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="af5e0-123">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-123">The name of the server DNS alias.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-126">サーバーの dns エイリアスを作成します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-126">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="af5e0-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string dnsAliasName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string dnsAliasName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iServerDnsAliasesOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, serverName, dnsAliasName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-130">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-130">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-131">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-131">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-132">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-132">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="af5e0-133">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-133">The name of the server DNS alias.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-136">指定された名前が付いたエイリアスが DNS サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-136">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-138">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string dnsAliasName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string dnsAliasName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;" Usage="iServerDnsAliasesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, dnsAliasName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-139">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-139">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-140">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-141">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-141">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="af5e0-142">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-142">The name of the server DNS alias.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-145">サーバーの dns エイリアスを作成します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-145">Creates a server dns alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-146">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="af5e0-147">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-147">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-148">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string dnsAliasName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string dnsAliasName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iServerDnsAliasesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, dnsAliasName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-149">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-149">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-150">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-150">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-151">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-151">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="af5e0-152">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-152">The name of the server DNS alias.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-155">指定された名前が付いたエイリアスが DNS サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-155">Deletes the server DNS alias with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-157">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-157">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string dnsAliasName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string dnsAliasName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;" Usage="iServerDnsAliasesOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, dnsAliasName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="dnsAliasName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-158">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-159">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-160">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-160">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="dnsAliasName">
            <span data-ttu-id="af5e0-161">サーバーの DNS エイリアスの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-161">The name of the server DNS alias.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-164">サーバーの DNS エイリアスを取得します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-164">Gets a server DNS alias.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="af5e0-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt; ListByServerNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt; ListByServerNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.ListByServerNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt;" Usage="iServerDnsAliasesOperations.ListByServerNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="af5e0-168">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="af5e0-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-171">サーバーのサーバーの DNS エイリアスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-171">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="af5e0-173">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt; ListByServerWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt; ListByServerWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations.ListByServerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt;" Usage="iServerDnsAliasesOperations.ListByServerWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerDnsAlias&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="af5e0-175">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-175">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="af5e0-176">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-176">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="af5e0-177">エイリアスがポイントして、サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="af5e0-177">The name of the server that the alias is pointing to.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="af5e0-178">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-178">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af5e0-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af5e0-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af5e0-180">サーバーのサーバーの DNS エイリアスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="af5e0-180">Gets a list of server DNS aliases for a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="af5e0-181">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="af5e0-182">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="af5e0-183">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="af5e0-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>