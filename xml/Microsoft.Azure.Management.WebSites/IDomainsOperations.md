<Type Name="IDomainsOperations" FullName="Microsoft.Azure.Management.WebSites.IDomainsOperations">
  <TypeSignature Language="C#" Value="public interface IDomainsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDomainsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.IDomainsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDomainsOperations" />
  <TypeSignature Language="F#" Value="type IDomainsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7201c-101">DomainsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="7201c-101">DomainsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.Domain * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="iDomainsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, domainName, domain, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-103">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-103">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="7201c-104">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="7201c-104">Domain registration information.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-107">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="7201c-107">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-108">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="7201c-108">Creates or updates a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;&gt; CheckAvailabilityWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;&gt; CheckAvailabilityWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.CheckAvailabilityWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.NameIdentifier,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAvailabilityWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.NameIdentifier * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;&gt;" Usage="iDomainsOperations.CheckAvailabilityWithHttpMessagesAsync (identifier, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="identifier">
            <span data-ttu-id="7201c-112">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-112">Name of the domain.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-115">登録の使用可能なドメインを確認します。</span><span class="sxs-lookup"><span data-stu-id="7201c-115">Check if a domain is available for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-116">登録の使用可能なドメインを確認します。</span><span class="sxs-lookup"><span data-stu-id="7201c-116">Check if a domain is available for registration.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-118">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;" Usage="iDomainsOperations.CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, domainOwnershipIdentifier, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-120">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-120">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-121">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-121">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7201c-122">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-122">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="7201c-123">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="7201c-123">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-126">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="7201c-126">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-127">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="7201c-127">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.Domain * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="iDomainsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, domainName, domain, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-131">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-132">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-132">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="7201c-133">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="7201c-133">Domain registration information.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-136">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="7201c-136">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-137">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="7201c-137">Creates or updates a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.DeleteOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteOwnershipIdentifierWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDomainsOperations.DeleteOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-141">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-141">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-142">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-142">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7201c-143">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-143">Name of identifier.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-146">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="7201c-146">Delete ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-147">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="7201c-147">Delete ownership identifier for domain</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDomainsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, domainName, forceHardDeleteDomain, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-150">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-150">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-151">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-151">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="7201c-152">指定&lt;コード&gt;true&lt;/code&gt;ドメインをすぐに削除します。</span><span class="sxs-lookup"><span data-stu-id="7201c-152">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="7201c-153">既定値は&lt;コード&gt;false&lt;/code&gt; 24 時間後に、ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="7201c-153">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-154">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-156">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="7201c-156">Delete a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-157">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="7201c-157">Delete a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-159">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;&gt; GetControlCenterSsoRequestWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;&gt; GetControlCenterSsoRequestWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.GetControlCenterSsoRequestWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetControlCenterSsoRequestWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;&gt;" Usage="iDomainsOperations.GetControlCenterSsoRequestWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7201c-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-162">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="7201c-162">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-163">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="7201c-163">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; GetOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; GetOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.GetOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOwnershipIdentifierWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;" Usage="iDomainsOperations.GetOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-167">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-167">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-168">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-168">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7201c-169">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-169">Name of identifier.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-172">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-172">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-173">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-173">Get ownership identifier for domain</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-174">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-174">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-175">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-175">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-176">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string domainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string domainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="iDomainsOperations.GetWithHttpMessagesAsync (resourceGroupName, domainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-177">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-177">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-178">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-178">Name of the domain.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-179">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-181">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-181">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-182">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-182">Get a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-184">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;" Usage="iDomainsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7201c-186">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7201c-186">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-189">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-189">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-190">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-190">Get all domains in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-191">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-191">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-192">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-192">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-193">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-193">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;" Usage="iDomainsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-194">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-194">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-195">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-197">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-197">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-198">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-198">Get all domains in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;" Usage="iDomainsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7201c-202">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7201c-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-203">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-203">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-204">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-205">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-205">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-206">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-206">Get all domains in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-207">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-207">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-208">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-208">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-209">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-209">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt; ListOwnershipIdentifiersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt; ListOwnershipIdentifiersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListOwnershipIdentifiersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOwnershipIdentifiersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt;" Usage="iDomainsOperations.ListOwnershipIdentifiersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7201c-210">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7201c-210">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-211">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-213">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7201c-213">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-214">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7201c-214">Lists domain ownership identifiers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-215">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-215">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-216">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-216">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-217">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-217">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt; ListOwnershipIdentifiersWithHttpMessagesAsync (string resourceGroupName, string domainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt; ListOwnershipIdentifiersWithHttpMessagesAsync(string resourceGroupName, string domainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListOwnershipIdentifiersWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOwnershipIdentifiersWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt;" Usage="iDomainsOperations.ListOwnershipIdentifiersWithHttpMessagesAsync (resourceGroupName, domainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-218">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-218">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-219">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-219">Name of domain.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-220">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-220">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-222">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7201c-222">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-223">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7201c-223">Lists domain ownership identifiers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-224">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-224">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-225">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-225">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-226">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-226">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt; ListRecommendationsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt; ListRecommendationsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListRecommendationsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRecommendationsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt;" Usage="iDomainsOperations.ListRecommendationsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7201c-227">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7201c-227">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-228">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-228">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-229">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-230">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-230">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-231">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-231">Get domain name recommendations based on keywords.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-232">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-232">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-233">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-233">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-234">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-234">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt; ListRecommendationsWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt; ListRecommendationsWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListRecommendationsWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRecommendationsWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt;" Usage="iDomainsOperations.ListRecommendationsWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="7201c-235">ドメイン名の推奨事項のパラメーターを検索します。</span><span class="sxs-lookup"><span data-stu-id="7201c-235">Search parameters for domain name recommendations.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-236">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-236">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-238">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-238">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-239">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-239">Get domain name recommendations based on keywords.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-240">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-240">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-241">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-241">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-242">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-242">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;" Usage="iDomainsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7201c-243">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-243">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-244">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-245">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-245">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-246">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7201c-246">Get all domains in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-247">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-247">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-248">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-248">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-249">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-249">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; UpdateOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; UpdateOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.UpdateOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateOwnershipIdentifierWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;" Usage="iDomainsOperations.UpdateOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, domainOwnershipIdentifier, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-250">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-250">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-251">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-251">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="7201c-252">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-252">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="7201c-253">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="7201c-253">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-254">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-254">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-256">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="7201c-256">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-257">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="7201c-257">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-258">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-258">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-259">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-259">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-260">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-260">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IDomainsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainPatchResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.DomainPatchResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="iDomainsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, domainName, domain, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7201c-261">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-261">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="7201c-262">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7201c-262">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="7201c-263">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="7201c-263">Domain registration information.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7201c-264">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7201c-264">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7201c-265">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7201c-265">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7201c-266">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="7201c-266">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7201c-267">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="7201c-267">Creates or updates a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7201c-268">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-268">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7201c-269">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-269">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7201c-270">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7201c-270">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>