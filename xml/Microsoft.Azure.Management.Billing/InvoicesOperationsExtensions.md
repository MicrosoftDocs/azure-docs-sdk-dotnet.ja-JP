<Type Name="InvoicesOperationsExtensions" FullName="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InvoicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InvoicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InvoicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InvoicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="71399-101">InvoicesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="71399-101">Extension methods for InvoicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Billing.Models.Invoice Get (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Billing.Models.Invoice Get(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.Get(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInvoicesOperations, invoiceName As String) As Invoice" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Billing.IInvoicesOperations * string -&gt; Microsoft.Azure.Management.Billing.Models.Invoice" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.Get (operations, invoiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.Invoice</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="invoiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-102">The operations group for this extension method.</span></span>
            </param>
        <param name="invoiceName">
            <span data-ttu-id="71399-103">請求書リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="71399-103">The name of an invoice resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-104">請求書の名前付きリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="71399-104">Gets a named invoice resource.</span></span> <span data-ttu-id="71399-105">単一の請求書を取得して、downloadUrl プロパティが自動的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="71399-105">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetAsync (operations, invoiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="invoiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-106">The operations group for this extension method.</span></span>
            </param>
        <param name="invoiceName">
            <span data-ttu-id="71399-107">請求書リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="71399-107">The name of an invoice resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71399-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71399-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-109">請求書の名前付きリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="71399-109">Gets a named invoice resource.</span></span> <span data-ttu-id="71399-110">単一の請求書を取得して、downloadUrl プロパティが自動的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="71399-110">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLatest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Billing.Models.Invoice GetLatest (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Billing.Models.Invoice GetLatest(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatest(Microsoft.Azure.Management.Billing.IInvoicesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLatest (operations As IInvoicesOperations) As Invoice" />
      <MemberSignature Language="F#" Value="static member GetLatest : Microsoft.Azure.Management.Billing.IInvoicesOperations -&gt; Microsoft.Azure.Management.Billing.Models.Invoice" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatest operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.Invoice</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-111">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-112">最新の請求書を取得します。</span><span class="sxs-lookup"><span data-stu-id="71399-112">Gets the most recent invoice.</span></span> <span data-ttu-id="71399-113">単一の請求書を取得して、downloadUrl プロパティが自動的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="71399-113">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLatestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetLatestAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetLatestAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatestAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetLatestAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;GetLatestAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-114">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71399-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71399-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-116">最新の請求書を取得します。</span><span class="sxs-lookup"><span data-stu-id="71399-116">Gets the most recent invoice.</span></span> <span data-ttu-id="71399-117">単一の請求書を取得して、downloadUrl プロパティが自動的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="71399-117">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; List (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; List(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.List(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IInvoicesOperations, Optional expand As String = null, Optional filter As String = null, Optional skiptoken As String = null, Optional top As Nullable(Of Integer) = null) As IPage(Of Invoice)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.List (operations, expand, filter, skiptoken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-118">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="71399-119">請求書の一覧内で downloadUrl プロパティを展開に使用できます。</span><span class="sxs-lookup"><span data-stu-id="71399-119">May be used to expand the downloadUrl property within a list of invoices.</span></span>
            <span data-ttu-id="71399-120">これにより、一度に複数の請求書を生成するダウンロード リンクできます。</span><span class="sxs-lookup"><span data-stu-id="71399-120">This enables download links to be generated for multiple invoices at once.</span></span>
            <span data-ttu-id="71399-121">既定では、請求書を一覧表示するときに downloadURLs は含まれません。</span><span class="sxs-lookup"><span data-stu-id="71399-121">By default, downloadURLs are not included when listing invoices.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="71399-122">InvoicePeriodEndDate して請求書をフィルター処理に使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="71399-122">May be used to filter invoices by invoicePeriodEndDate.</span></span> <span data-ttu-id="71399-123">フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。</span><span class="sxs-lookup"><span data-stu-id="71399-123">The filter supports 'eq', 'lt', 'gt', 'le', 'ge', and 'and'.</span></span> <span data-ttu-id="71399-124">これはサポートされていません"ne"'または' または 'not' です。</span><span class="sxs-lookup"><span data-stu-id="71399-124">It does not currently support 'ne', 'or', or 'not'.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="71399-125">Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="71399-125">Skiptoken is only used if a previous operation returned a partial result.</span></span>
            <span data-ttu-id="71399-126">前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。</span><span class="sxs-lookup"><span data-stu-id="71399-126">If a previous response contains a nextLink element, the value of the nextLink element will include a skiptoken parameter that specifies a starting point to use for subsequent calls.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="71399-127">最新の N 請求書に結果の数を制限するために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="71399-127">May be used to limit the number of results to the most recent N invoices.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-128">最新の請求書による順の先頭でサブスクリプションの利用可能な請求書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="71399-128">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="71399-129">プレビューでは、請求書は、2016 年 12 月 1 日を終了する請求期間にのみ、この API を使用して利用可能な以降です。</span><span class="sxs-lookup"><span data-stu-id="71399-129">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListAsync (operations, expand, filter, skiptoken, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-130">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="71399-131">請求書の一覧内で downloadUrl プロパティを展開に使用できます。</span><span class="sxs-lookup"><span data-stu-id="71399-131">May be used to expand the downloadUrl property within a list of invoices.</span></span>
            <span data-ttu-id="71399-132">これにより、一度に複数の請求書を生成するダウンロード リンクできます。</span><span class="sxs-lookup"><span data-stu-id="71399-132">This enables download links to be generated for multiple invoices at once.</span></span>
            <span data-ttu-id="71399-133">既定では、請求書を一覧表示するときに downloadURLs は含まれません。</span><span class="sxs-lookup"><span data-stu-id="71399-133">By default, downloadURLs are not included when listing invoices.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="71399-134">InvoicePeriodEndDate して請求書をフィルター処理に使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="71399-134">May be used to filter invoices by invoicePeriodEndDate.</span></span> <span data-ttu-id="71399-135">フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。</span><span class="sxs-lookup"><span data-stu-id="71399-135">The filter supports 'eq', 'lt', 'gt', 'le', 'ge', and 'and'.</span></span> <span data-ttu-id="71399-136">これはサポートされていません"ne"'または' または 'not' です。</span><span class="sxs-lookup"><span data-stu-id="71399-136">It does not currently support 'ne', 'or', or 'not'.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="71399-137">Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="71399-137">Skiptoken is only used if a previous operation returned a partial result.</span></span>
            <span data-ttu-id="71399-138">前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。</span><span class="sxs-lookup"><span data-stu-id="71399-138">If a previous response contains a nextLink element, the value of the nextLink element will include a skiptoken parameter that specifies a starting point to use for subsequent calls.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="71399-139">最新の N 請求書に結果の数を制限するために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="71399-139">May be used to limit the number of results to the most recent N invoices.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71399-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71399-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-141">最新の請求書による順の先頭でサブスクリプションの利用可能な請求書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="71399-141">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="71399-142">プレビューでは、請求書は、2016 年 12 月 1 日を終了する請求期間にのみ、この API を使用して利用可能な以降です。</span><span class="sxs-lookup"><span data-stu-id="71399-142">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; ListNext (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; ListNext(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNext(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IInvoicesOperations, nextPageLink As String) As IPage(Of Invoice)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Billing.IInvoicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-143">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71399-144">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71399-144">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-145">最新の請求書による順の先頭でサブスクリプションの利用可能な請求書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="71399-145">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="71399-146">プレビューでは、請求書は、2016 年 12 月 1 日を終了する請求期間にのみ、この API を使用して利用可能な以降です。</span><span class="sxs-lookup"><span data-stu-id="71399-146">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71399-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71399-147">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71399-148">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71399-148">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71399-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71399-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71399-150">最新の請求書による順の先頭でサブスクリプションの利用可能な請求書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="71399-150">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="71399-151">プレビューでは、請求書は、2016 年 12 月 1 日を終了する請求期間にのみ、この API を使用して利用可能な以降です。</span><span class="sxs-lookup"><span data-stu-id="71399-151">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>