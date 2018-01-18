<Type Name="IDomainsOperations" FullName="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations">
  <TypeSignature Language="C#" Value="public interface IDomainsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDomainsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDomainsOperations" />
  <TypeSignature Language="F#" Value="type IDomainsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1e35-101">DomainsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-101">DomainsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="iDomainsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, domainName, domain, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d1e35-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-103">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-103">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="d1e35-104">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="d1e35-104">Domain registration information.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-107">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-107">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-108">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-108">Creates or updates a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;&gt; CheckAvailabilityWithHttpMessagesAsync (Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;&gt; CheckAvailabilityWithHttpMessagesAsync(class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.CheckAvailabilityWithHttpMessagesAsync(Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAvailabilityWithHttpMessagesAsync : Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;&gt;" Usage="iDomainsOperations.CheckAvailabilityWithHttpMessagesAsync (identifier, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="identifier">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="iDomainsOperations.CreateOrUpdateOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, domainOwnershipIdentifier, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d1e35-112">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-112">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-113">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-113">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="d1e35-114">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-114">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="d1e35-115">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="d1e35-115">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-118">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-118">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-119">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-119">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="iDomainsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, domainName, domain, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d1e35-123">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-123">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-124">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-124">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="d1e35-125">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="d1e35-125">Domain registration information.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-128">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-128">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-129">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-129">Creates or updates a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.DeleteOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteOwnershipIdentifierWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDomainsOperations.DeleteOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="d1e35-133">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-134">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-134">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="d1e35-135">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-135">Name of identifier.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-138">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-138">Delete ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-139">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-139">Delete ownership identifier for domain</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDomainsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, domainName, forceHardDeleteDomain, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="d1e35-142">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-142">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-143">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-143">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="d1e35-144">指定&lt;コード&gt;true&lt;/code&gt;ドメインをすぐに削除します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-144">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="d1e35-145">既定値は&lt;コード&gt;false&lt;/code&gt; 24 時間後に、ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-145">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-148">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-148">Delete a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-149">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-149">Delete a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-150">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;&gt; GetControlCenterSsoRequestWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;&gt; GetControlCenterSsoRequestWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.GetControlCenterSsoRequestWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetControlCenterSsoRequestWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;&gt;" Usage="iDomainsOperations.GetControlCenterSsoRequestWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-152">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-152">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-154">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-154">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-155">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-155">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; GetOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; GetOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.GetOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOwnershipIdentifierWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="iDomainsOperations.GetOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
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
            <span data-ttu-id="d1e35-159">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-160">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-160">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="d1e35-161">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-161">Name of identifier.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-164">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-164">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-165">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-165">Get ownership identifier for domain</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-166">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-167">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-168">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string domainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string domainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="iDomainsOperations.GetWithHttpMessagesAsync (resourceGroupName, domainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d1e35-169">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-169">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-170">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-170">Name of the domain.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-171">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-171">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-173">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-173">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-174">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-174">Get a domain.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-175">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-175">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-176">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-176">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-177">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-177">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d1e35-178">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-178">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-179">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-181">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-181">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-182">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-182">Get all domains in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-184">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d1e35-186">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-186">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-189">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-189">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-190">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-190">Get all domains in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-191">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-191">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-192">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-192">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-193">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-193">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d1e35-194">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-194">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-195">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-197">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-197">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-198">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-198">Get all domains in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt; ListOwnershipIdentifiersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt; ListOwnershipIdentifiersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListOwnershipIdentifiersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOwnershipIdentifiersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListOwnershipIdentifiersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d1e35-202">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-203">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-203">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-204">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-205">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-205">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-206">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-206">Lists domain ownership identifiers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-207">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-207">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-208">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-208">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-209">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-209">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt; ListOwnershipIdentifiersWithHttpMessagesAsync (string resourceGroupName, string domainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt; ListOwnershipIdentifiersWithHttpMessagesAsync(string resourceGroupName, string domainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListOwnershipIdentifiersWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOwnershipIdentifiersWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListOwnershipIdentifiersWithHttpMessagesAsync (resourceGroupName, domainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d1e35-210">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-210">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-211">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-211">Name of domain.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-212">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-212">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-214">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-214">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-215">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-215">Lists domain ownership identifiers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-216">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-216">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-217">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-217">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-218">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-218">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt; ListRecommendationsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt; ListRecommendationsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListRecommendationsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRecommendationsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListRecommendationsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt; ListRecommendationsWithHttpMessagesAsync (Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt; ListRecommendationsWithHttpMessagesAsync(class Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListRecommendationsWithHttpMessagesAsync(Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRecommendationsWithHttpMessagesAsync : Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListRecommendationsWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;" Usage="iDomainsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-219">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-219">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-221">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-221">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-222">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-222">Get all domains in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-223">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-223">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-224">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-224">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-225">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-225">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifierWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; UpdateOwnershipIdentifierWithHttpMessagesAsync (string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; UpdateOwnershipIdentifierWithHttpMessagesAsync(string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations.UpdateOwnershipIdentifierWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateOwnershipIdentifierWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="iDomainsOperations.UpdateOwnershipIdentifierWithHttpMessagesAsync (resourceGroupName, domainName, name, domainOwnershipIdentifier, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d1e35-226">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-226">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="d1e35-227">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-227">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="d1e35-228">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="d1e35-228">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="d1e35-229">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="d1e35-229">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d1e35-230">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-230">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d1e35-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d1e35-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d1e35-232">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-232">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d1e35-233">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="d1e35-233">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d1e35-234">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-234">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d1e35-235">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-235">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d1e35-236">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d1e35-236">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>