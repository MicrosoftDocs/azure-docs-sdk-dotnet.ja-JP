<Type Name="TopLevelDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopLevelDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopLevelDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopLevelDomainsOperationsExtensions = class" />
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
            <span data-ttu-id="847d6-101">TopLevelDomainsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="847d6-101">Extension methods for TopLevelDomainsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.GetAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="847d6-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="847d6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="847d6-103">トップレベル ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="847d6-103">Name of the top-level domain.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="847d6-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="847d6-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="847d6-105">最上位ドメインの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="847d6-105">Get details of a top-level domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="847d6-106">最上位ドメインの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="847d6-106">Get details of a top-level domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner agreementOption, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner agreementOption, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsAsync (operations, name, agreementOption, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="agreementOption" Type="Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainAgreementOptionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="name">To be added.</param>
        <param name="agreementOption">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAgreementsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt; ListAgreementsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAgreementsNextAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAgreementsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAgreementsNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TldLegalAgreement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="847d6-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="847d6-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="847d6-108">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="847d6-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="847d6-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="847d6-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="847d6-110">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="847d6-110">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="847d6-111">すべての法的な契約を取得するユーザーは、ドメインを購入する前にそのまま使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="847d6-111">Gets all legal agreements that user needs to accept before purchasing a domain.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="847d6-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="847d6-112">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="847d6-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="847d6-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="847d6-114">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="847d6-114">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="847d6-115">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="847d6-115">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.TopLevelDomainsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.TopLevelDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.ITopLevelDomainsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="847d6-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="847d6-116">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="847d6-117">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="847d6-117">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="847d6-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="847d6-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="847d6-119">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="847d6-119">Get all top-level domains supported for registration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="847d6-120">登録のサポートされているすべてのトップレベル ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="847d6-120">Get all top-level domains supported for registration.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>