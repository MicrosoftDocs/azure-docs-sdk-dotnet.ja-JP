<Type Name="DomainsOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="da692-101">DomainsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="da692-101">Extension methods for DomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain BeginCreateOrUpdate (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain BeginCreateOrUpdate(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, domainName, domain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-104">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-104">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="da692-105">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="da692-105">Domain registration information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-106">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-106">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-107">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-107">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-109">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-109">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-110">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-110">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="da692-111">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="da692-111">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-113">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-113">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-114">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-114">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult CheckAvailability (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult CheckAvailability(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.NameIdentifier)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As IDomainsOperations, identifier As NameIdentifier) As DomainAvailablilityCheckResult" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.NameIdentifier -&gt; Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailability (operations, identifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-115">The operations group for this extension method.</span></span>
            </param>
        <param name="identifier">
            <span data-ttu-id="da692-116">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-116">Name of the domain.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-117">登録の使用可能なドメインを確認します。</span><span class="sxs-lookup"><span data-stu-id="da692-117">Check if a domain is available for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-118">登録の使用可能なドメインを確認します。</span><span class="sxs-lookup"><span data-stu-id="da692-118">Check if a domain is available for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.NameIdentifier identifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.NameIdentifier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.NameIdentifier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CheckAvailabilityAsync (operations, identifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainAvailablilityCheckResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-119">The operations group for this extension method.</span></span>
            </param>
        <param name="identifier">
            <span data-ttu-id="da692-120">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-120">Name of the domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-122">登録の使用可能なドメインを確認します。</span><span class="sxs-lookup"><span data-stu-id="da692-122">Check if a domain is available for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-123">登録の使用可能なドメインを確認します。</span><span class="sxs-lookup"><span data-stu-id="da692-123">Check if a domain is available for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain CreateOrUpdate (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain CreateOrUpdate(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, domainName, domain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-125">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-126">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-126">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="da692-127">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="da692-127">Domain registration information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-128">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-128">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-129">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-129">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.Domain domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.Domain domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.Domain,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.Domain * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.Domain" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-131">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-132">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-132">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="da692-133">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="da692-133">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-135">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-135">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-136">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-136">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier CreateOrUpdateOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier CreateOrUpdateOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier -&gt; Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifier (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-138">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-138">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-139">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-139">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-140">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-140">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="da692-141">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="da692-141">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-142">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-142">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-143">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-143">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; CreateOrUpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; CreateOrUpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;CreateOrUpdateOwnershipIdentifierAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-145">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-145">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-146">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-146">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-147">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-147">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="da692-148">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="da692-148">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-150">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-150">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-151">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-151">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Delete(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDomainsOperations, resourceGroupName As String, domainName As String, Optional forceHardDeleteDomain As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Delete (operations, resourceGroupName, domainName, forceHardDeleteDomain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-153">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-153">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-154">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-154">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="da692-155">指定&lt;コード&gt;true&lt;/code&gt;ドメインをすぐに削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-155">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="da692-156">既定値は&lt;コード&gt;false&lt;/code&gt; 24 時間後に、ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-156">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-157">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-157">Delete a domain.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="da692-158">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-158">Delete a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, domainName, forceHardDeleteDomain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;DeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-160">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-160">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-161">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-161">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="da692-162">指定&lt;コード&gt;true&lt;/code&gt;ドメインをすぐに削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-162">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="da692-163">既定値は&lt;コード&gt;false&lt;/code&gt; 24 時間後に、ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-163">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-165">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-165">Delete a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-166">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-166">Delete a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static void DeleteOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteOwnershipIdentifier (operations As IDomainsOperations, resourceGroupName As String, domainName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member DeleteOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifier (operations, resourceGroupName, domainName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-168">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-168">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-169">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-169">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-170">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-170">Name of identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-171">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-171">Delete ownership identifier for domain</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="da692-172">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-172">Delete ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;DeleteOwnershipIdentifierAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-174">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-174">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-175">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-175">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-176">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-176">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-178">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-178">Delete ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-179">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="da692-179">Delete ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain Get (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain Get(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDomainsOperations, resourceGroupName As String, domainName As String) As Domain" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Get (operations, resourceGroupName, domainName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-181">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-181">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-182">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-182">Name of the domain.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-183">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-183">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-184">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-184">Get a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; GetAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; GetAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;GetAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-186">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-186">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-187">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-187">Name of the domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-189">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-189">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-190">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-190">Get a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest GetControlCenterSsoRequest (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest GetControlCenterSsoRequest(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequest(Microsoft.Azure.Management.WebSites.IDomainsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetControlCenterSsoRequest (operations As IDomainsOperations) As DomainControlCenterSsoRequest" />
      <MemberSignature Language="F#" Value="static member GetControlCenterSsoRequest : Microsoft.Azure.Management.WebSites.IDomainsOperations -&gt; Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequest operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-191">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-192">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="da692-192">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-193">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="da692-193">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt; GetControlCenterSsoRequestAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt; GetControlCenterSsoRequestAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetControlCenterSsoRequestAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;GetControlCenterSsoRequestAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainControlCenterSsoRequest&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-194">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-196">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="da692-196">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-197">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="da692-197">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier GetOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier GetOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOwnershipIdentifier (operations As IDomainsOperations, resourceGroupName As String, domainName As String, name As String) As DomainOwnershipIdentifier" />
      <MemberSignature Language="F#" Value="static member GetOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifier (operations, resourceGroupName, domainName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-199">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-199">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-200">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-200">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-201">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-201">Name of identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-202">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-202">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-203">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-203">Get ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; GetOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; GetOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.GetOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;GetOwnershipIdentifierAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-205">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-205">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-206">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-206">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-207">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-207">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-209">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-209">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-210">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-210">Get ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; List (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; List(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IDomainsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDomainsOperations) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IDomainsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-211">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-211">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-212">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-212">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-213">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-213">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-214">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-215">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-216">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-216">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-217">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-217">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroup (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroup(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IDomainsOperations, resourceGroupName As String) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-219">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-219">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-220">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-220">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-221">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-221">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-222">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-223">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-223">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-225">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-225">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-226">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-226">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-227">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-227">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-228">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-228">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-229">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-229">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-230">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-230">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-231">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-231">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-232">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-232">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-233">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-234">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-234">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-235">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-235">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; ListNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of Domain)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-236">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-237">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-237">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-238">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-238">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-239">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-239">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-241">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-242">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-243">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-243">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-244">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-244">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiers">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiers (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiers(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiers(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOwnershipIdentifiers (operations As IDomainsOperations, resourceGroupName As String, domainName As String) As IPage(Of DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiers : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiers (operations, resourceGroupName, domainName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-245">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-245">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-246">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-246">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-247">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-247">Name of domain.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-248">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-248">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-249">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-249">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-250">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-250">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-251">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-251">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-252">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-252">Name of domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-253">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-254">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-254">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-255">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-255">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiersNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; ListOwnershipIdentifiersNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOwnershipIdentifiersNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-256">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-257">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-257">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-258">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-258">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-259">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-259">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt; ListOwnershipIdentifiersNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-260">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-261">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-261">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-262">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-263">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-263">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-264">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="da692-264">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendations">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendations (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendations(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendations(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRecommendations (operations As IDomainsOperations, parameters As DomainRecommendationSearchParameters) As IPage(Of NameIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListRecommendations : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendations (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-265">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="da692-266">ドメイン名の推奨事項のパラメーターを検索します。</span><span class="sxs-lookup"><span data-stu-id="da692-266">Search parameters for domain name recommendations.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-267">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-267">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-268">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-268">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, class Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListRecommendationsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.DomainRecommendationSearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-269">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-269">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="da692-270">ドメイン名の推奨事項のパラメーターを検索します。</span><span class="sxs-lookup"><span data-stu-id="da692-270">Search parameters for domain name recommendations.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-272">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-272">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-273">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-273">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendationsNext (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt; ListRecommendationsNext(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNext(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRecommendationsNext (operations As IDomainsOperations, nextPageLink As String) As IPage(Of NameIdentifier)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsNext : Microsoft.Azure.Management.WebSites.IDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-274">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-274">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-275">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-275">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-276">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-276">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-277">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-277">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsNextAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt; ListRecommendationsNextAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNextAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsNextAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.ListRecommendationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;ListRecommendationsNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.NameIdentifier&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-278">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-278">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="da692-279">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="da692-279">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-280">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-281">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-281">Get domain name recommendations based on keywords.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-282">含まれるキーワードに基づいて、ドメイン名に関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="da692-282">Get domain name recommendations based on keywords.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.Domain Update (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.Domain Update(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Update(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainPatchResource)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.DomainPatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.Domain" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.Update (operations, resourceGroupName, domainName, domain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.Domain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-283">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-284">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-284">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-285">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-285">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="da692-286">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="da692-286">Domain registration information.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-287">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-287">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-288">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-288">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt; UpdateAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.Domain&gt; UpdateAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.WebSites.Models.DomainPatchResource domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainPatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * Microsoft.Azure.Management.WebSites.Models.DomainPatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;UpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.Domain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.WebSites.Models.DomainPatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-289">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-289">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-290">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-290">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-291">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-291">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="da692-292">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="da692-292">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-293">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-293">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-294">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-294">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-295">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="da692-295">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier UpdateOwnershipIdentifier (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier UpdateOwnershipIdentifier(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifier(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier)" />
      <MemberSignature Language="F#" Value="static member UpdateOwnershipIdentifier : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier -&gt; Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifier (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-297">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-297">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-298">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-298">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-299">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-299">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="da692-300">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="da692-300">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-301">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-301">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-302">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-302">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; UpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt; UpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.WebSites.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.WebSites.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.WebSites.IDomainsOperations * string * string * string * Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;" Usage="Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.DomainsOperationsExtensions/&lt;UpdateOwnershipIdentifierAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.DomainOwnershipIdentifier" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="da692-303">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="da692-303">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="da692-304">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-304">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="da692-305">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-305">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="da692-306">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="da692-306">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="da692-307">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="da692-307">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="da692-308">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="da692-308">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="da692-309">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-309">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="da692-310">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="da692-310">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>