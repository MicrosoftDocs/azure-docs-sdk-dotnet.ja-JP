<Type Name="TopLevelDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopLevelDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopLevelDomainsOperationsExtensions = class" />
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
            <span data-ttu-id="9c7f0-101">TopLevelDomainsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-101">Extension methods for TopLevelDomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.TopLevelDomain Get (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.TopLevelDomain Get(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITopLevelDomainsOperations, name As String) As TopLevelDomain" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string -&gt; Microsoft.Azure.Management.WebSites.Models.TopLevelDomain" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.Get (operations, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.TopLevelDomain</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c7f0-103">トップレベル ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-103">Name of the top-level domain.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-104">最上位ドメインの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-104">Get details of a top-level domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-105">最上位ドメインの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-105">Get details of a top-level domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt; GetAsync (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt; GetAsync(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.GetAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-106">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c7f0-107">トップレベル ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-107">Name of the top-level domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c7f0-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-109">最上位ドメインの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-109">Get details of a top-level domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-110">最上位ドメインの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-110">Get details of a top-level domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt; List (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt; List(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.List(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ITopLevelDomainsOperations) As IPage(Of TopLevelDomain)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-111">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-112">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-112">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-113">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-113">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreements">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt; ListAgreements (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name, Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption agreementOption);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt; ListAgreements(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name, class Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption agreementOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreements(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String,Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAgreements (operations As ITopLevelDomainsOperations, name As String, agreementOption As TopLevelDomainAgreementOption) As IPage(Of TldLegalAgreement)" />
      <MemberSignature Language="F#" Value="static member ListAgreements : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string * Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreements (operations, name, agreementOption)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="agreementOption" Type="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-114">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c7f0-115">トップレベル ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-115">Name of the top-level domain.</span></span>
            </param>
        <param name="agreementOption">
            <span data-ttu-id="9c7f0-116">アグリーメントのドメイン オプション。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-116">Domain agreement options.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-117">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-117">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-118">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-118">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name, Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption agreementOption, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string name, class Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption agreementOption, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreementsAsync(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String,Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsAsync : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string * Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreementsAsync (operations, name, agreementOption, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="agreementOption" Type="Microsoft.Azure.Management.WebSites.Models.TopLevelDomainAgreementOption" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-119">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c7f0-120">トップレベル ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-120">Name of the top-level domain.</span></span>
            </param>
        <param name="agreementOption">
            <span data-ttu-id="9c7f0-121">アグリーメントのドメイン オプション。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-121">Domain agreement options.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c7f0-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-123">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-123">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-124">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-124">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt; ListAgreementsNext (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt; ListAgreementsNext(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreementsNext(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAgreementsNext (operations As ITopLevelDomainsOperations, nextPageLink As String) As IPage(Of TldLegalAgreement)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsNext : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreementsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-125">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c7f0-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-127">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-127">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-128">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-128">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsNextAsync : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-129">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c7f0-130">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-130">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c7f0-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-132">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-132">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-133">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-133">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-134">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c7f0-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-136">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-136">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-137">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-137">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt; ListNext (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt; ListNext(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ITopLevelDomainsOperations, nextPageLink As String) As IPage(Of TopLevelDomain)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-138">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c7f0-139">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-139">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-140">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-140">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-141">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-141">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.TopLevelDomainsOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.TopLevelDomain&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c7f0-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-142">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c7f0-143">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-143">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c7f0-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c7f0-145">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-145">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="9c7f0-146">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c7f0-146">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>