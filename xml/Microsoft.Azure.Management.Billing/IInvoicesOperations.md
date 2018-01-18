<Type Name="IInvoicesOperations" FullName="Microsoft.Azure.Management.Billing.IInvoicesOperations">
  <TypeSignature Language="C#" Value="public interface IInvoicesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IInvoicesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.IInvoicesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IInvoicesOperations" />
  <TypeSignature Language="F#" Value="type IInvoicesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0d93-101">InvoicesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c0d93-101">InvoicesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetLatestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; GetLatestWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; GetLatestWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.IInvoicesOperations.GetLatestWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLatestWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="iInvoicesOperations.GetLatestWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="c0d93-102">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-102">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0d93-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0d93-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0d93-104">最新の請求書を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-104">Gets the most recent invoice.</span></span> <span data-ttu-id="c0d93-105">単一の請求書を取得して、downloadUrl プロパティが自動的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-105">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Billing.Models.ErrorResponseException">
            <span data-ttu-id="c0d93-106">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0d93-107">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0d93-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; GetWithHttpMessagesAsync (string invoiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; GetWithHttpMessagesAsync(string invoiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.IInvoicesOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="iInvoicesOperations.GetWithHttpMessagesAsync (invoiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="invoiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="invoiceName">
            <span data-ttu-id="c0d93-109">請求書リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="c0d93-109">The name of an invoice resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0d93-110">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-110">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0d93-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0d93-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0d93-112">請求書の名前付きリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-112">Gets a named invoice resource.</span></span> <span data-ttu-id="c0d93-113">単一の請求書を取得して、downloadUrl プロパティが自動的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-113">When getting a single invoice, the downloadUrl property is expanded automatically.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Billing.Models.ErrorResponseException">
            <span data-ttu-id="c0d93-114">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0d93-115">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-115">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0d93-116">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-116">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.IInvoicesOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt;" Usage="iInvoicesOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c0d93-117">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c0d93-117">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0d93-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0d93-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0d93-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0d93-120">最新の請求書による順の先頭でサブスクリプションの利用可能な請求書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-120">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="c0d93-121">プレビューでは、請求書は、2016 年 12 月 1 日を終了する請求期間にのみ、この API を使用して利用可能な以降です。</span><span class="sxs-lookup"><span data-stu-id="c0d93-121">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Billing.Models.ErrorResponseException">
            <span data-ttu-id="c0d93-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0d93-123">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-123">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0d93-124">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-124">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt; ListWithHttpMessagesAsync (string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt; ListWithHttpMessagesAsync(string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.IInvoicesOperations.ListWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt;" Usage="iInvoicesOperations.ListWithHttpMessagesAsync (expand, filter, skiptoken, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="expand">
            <span data-ttu-id="c0d93-125">請求書の一覧内で downloadUrl プロパティを展開に使用できます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-125">May be used to expand the downloadUrl property within a list of invoices.</span></span> <span data-ttu-id="c0d93-126">これにより、一度に複数の請求書を生成するダウンロード リンクできます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-126">This enables download links to be generated for multiple invoices at once.</span></span> <span data-ttu-id="c0d93-127">既定では、請求書を一覧表示するときに downloadURLs は含まれません。</span><span class="sxs-lookup"><span data-stu-id="c0d93-127">By default, downloadURLs are not included when listing invoices.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="c0d93-128">InvoicePeriodEndDate して請求書をフィルター処理に使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c0d93-128">May be used to filter invoices by invoicePeriodEndDate.</span></span> <span data-ttu-id="c0d93-129">フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。</span><span class="sxs-lookup"><span data-stu-id="c0d93-129">The filter supports 'eq', 'lt', 'gt', 'le', 'ge', and 'and'.</span></span> <span data-ttu-id="c0d93-130">これはサポートされていません"ne"'または' または 'not' です。</span><span class="sxs-lookup"><span data-stu-id="c0d93-130">It does not currently support 'ne', 'or', or 'not'.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="c0d93-131">Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-131">Skiptoken is only used if a previous operation returned a partial result.</span></span> <span data-ttu-id="c0d93-132">前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-132">If a previous response contains a nextLink element, the value of the nextLink element will include a skiptoken parameter that specifies a starting point to use for subsequent calls.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c0d93-133">最新の N 請求書に結果の数を制限するために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c0d93-133">May be used to limit the number of results to the most recent N invoices.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0d93-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0d93-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0d93-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0d93-136">最新の請求書による順の先頭でサブスクリプションの利用可能な請求書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0d93-136">Lists the available invoices for a subscription in reverse chronological order beginning with the most recent invoice.</span></span> <span data-ttu-id="c0d93-137">プレビューでは、請求書は、2016 年 12 月 1 日を終了する請求期間にのみ、この API を使用して利用可能な以降です。</span><span class="sxs-lookup"><span data-stu-id="c0d93-137">In preview, invoices are available via this API only for invoice periods which end December 1, 2016 or later.</span></span>
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Billing.Models.ErrorResponseException">
            <span data-ttu-id="c0d93-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0d93-139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0d93-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0d93-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>