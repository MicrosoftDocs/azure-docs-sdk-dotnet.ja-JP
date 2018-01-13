<Type Name="DomainsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DomainsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9a7e0-101">DomainsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-101">Extension methods for DomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-104">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-104">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="9a7e0-105">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-105">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-107">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-107">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-108">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-108">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner identifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CheckAvailabilityAsync (operations, identifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainAvailablilityCheckResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="identifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="identifier">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, domainName, domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-111">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-111">Name of the domain.</span></span>
            </param>
        <param name="domain">
            <span data-ttu-id="9a7e0-112">ドメインの登録情報。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-112">Domain registration information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-114">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-114">Creates or updates a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-115">作成するか、ドメインを更新します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-115">Creates or updates a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; CreateOrUpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; CreateOrUpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.CreateOrUpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;CreateOrUpdateOwnershipIdentifierAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-117">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-117">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-118">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-118">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9a7e0-119">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-119">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="9a7e0-120">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-120">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-122">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-122">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-123">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-123">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, Nullable&lt;bool&gt; forceHardDeleteDomain = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Nullable`1&lt;bool&gt; forceHardDeleteDomain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, domainName, forceHardDeleteDomain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="forceHardDeleteDomain" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-125">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-126">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-126">Name of the domain.</span></span>
            </param>
        <param name="forceHardDeleteDomain">
            <span data-ttu-id="9a7e0-127">指定&lt;コード&gt;true&lt;/code&gt;ドメインをすぐに削除します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-127">Specify &lt;code&gt;true&lt;/code&gt; to delete the domain immediately.</span></span> <span data-ttu-id="9a7e0-128">既定値は&lt;コード&gt;false&lt;/code&gt; 24 時間後に、ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-128">The default is &lt;code&gt;false&lt;/code&gt; which deletes the domain after 24 hours.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-130">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-130">Delete a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-131">ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-131">Delete a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.DeleteOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;DeleteOwnershipIdentifierAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-133">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-134">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-134">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9a7e0-135">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-135">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-137">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-137">Delete ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-138">ドメインの所有権の識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-138">Delete ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-140">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-140">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-141">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-141">Name of the domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-143">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-143">Get a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-144">ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-144">Get a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetControlCenterSsoRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt; GetControlCenterSsoRequestAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt; GetControlCenterSsoRequestAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetControlCenterSsoRequestAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetControlCenterSsoRequestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetControlCenterSsoRequestAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainControlCenterSsoRequestInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-145">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-147">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-147">Generate a single sign-on request for the domain management portal.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-148">ドメインの管理ポータルの 1 つのサインオン要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-148">Generate a single sign-on request for the domain management portal.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; GetOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; GetOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.GetOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;GetOwnershipIdentifierAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-150">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-150">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-151">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-151">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9a7e0-152">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-152">Name of identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-154">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-154">Get ownership identifier for domain</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-155">ドメインの所有権の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-155">Get ownership identifier for domain</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-156">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-158">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-158">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-159">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-159">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-161">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-161">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-163">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-163">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-164">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-164">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-165">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9a7e0-166">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-166">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-168">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-168">Get all domains in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-169">リソース グループ内のすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-169">Get all domains in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9a7e0-171">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-173">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-173">Get all domains in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-174">サブスクリプションのすべてのドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-174">Get all domains in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersAsync (operations, resourceGroupName, domainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-176">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-176">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-177">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-177">Name of domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-179">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-179">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-180">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-180">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOwnershipIdentifiersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt; ListOwnershipIdentifiersNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOwnershipIdentifiersNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListOwnershipIdentifiersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListOwnershipIdentifiersNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-181">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9a7e0-182">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-184">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-184">Lists domain ownership identifiers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-185">ドメインの所有権の識別子を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-185">Lists domain ownership identifiers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListRecommendationsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainRecommendationSearchParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendationsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt; ListRecommendationsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendationsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.ListRecommendationsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;ListRecommendationsNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateOwnershipIdentifierAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; UpdateOwnershipIdentifierAsync (this Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt; UpdateOwnershipIdentifierAsync(class Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations operations, string resourceGroupName, string domainName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner domainOwnershipIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync(Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateOwnershipIdentifierAsync : Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions.UpdateOwnershipIdentifierAsync (operations, resourceGroupName, domainName, name, domainOwnershipIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.DomainsOperationsExtensions/&lt;UpdateOwnershipIdentifierAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="domainName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="domainOwnershipIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainOwnershipIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9a7e0-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9a7e0-187">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="domainName">
            <span data-ttu-id="9a7e0-188">ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-188">Name of domain.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9a7e0-189">識別子の名前です。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-189">Name of identifier.</span></span>
            </param>
        <param name="domainOwnershipIdentifier">
            <span data-ttu-id="9a7e0-190">ドメインの所有権プロパティの JSON 表現。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-190">A JSON representation of the domain ownership properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9a7e0-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9a7e0-192">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-192">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9a7e0-193">ドメインまたは更新プログラムの識別子の所有権の識別子を既存の識別子の詳細を作成します。</span><span class="sxs-lookup"><span data-stu-id="9a7e0-193">Creates an ownership identifier for a domain or updates identifier details for an existing identifer</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>