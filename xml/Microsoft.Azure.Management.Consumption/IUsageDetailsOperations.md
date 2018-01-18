<Type Name="IUsageDetailsOperations" FullName="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations">
  <TypeSignature Language="C#" Value="public interface IUsageDetailsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUsageDetailsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUsageDetailsOperations" />
  <TypeSignature Language="F#" Value="type IUsageDetailsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ebf04-101">UsageDetailsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="ebf04-101">UsageDetailsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;" Usage="iUsageDetailsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="ebf04-102">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ebf04-102">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ebf04-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ebf04-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ebf04-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ebf04-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ebf04-105">請求期間使用して、スコープの使用方法の詳細を示します。</span><span class="sxs-lookup"><span data-stu-id="ebf04-105">Lists the usage details for a scope by billing period.</span></span> <span data-ttu-id="ebf04-106">使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-106">Usage details are available via this API only for May 1, 2014 or later.</span></span>
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponseException">
            <span data-ttu-id="ebf04-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ebf04-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ebf04-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListWithHttpMessagesAsync (string scope, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt; ListWithHttpMessagesAsync(string scope, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.IUsageDetailsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;" Usage="iUsageDetailsOperations.ListWithHttpMessagesAsync (scope, expand, filter, skiptoken, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="ebf04-110">使用方法の詳細のスコープです。</span><span class="sxs-lookup"><span data-stu-id="ebf04-110">The scope of the usage details.</span></span> <span data-ttu-id="ebf04-111">スコープは、'/サブスクリプション/{subscriptionid} ' サブスクリプションの場合または '/subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}' の課金 perdiod です。</span><span class="sxs-lookup"><span data-stu-id="ebf04-111">The scope can be '/subscriptions/{subscriptionId}' for a subscription, or '/subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}' for a billing perdiod.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="ebf04-112">プロパティ/additionalProperties またはプロパティ/meterDetails 内での使用方法の詳細の一覧を展開して使用できます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-112">May be used to expand the properties/additionalProperties or properties/meterDetails within a list of usage details.</span></span> <span data-ttu-id="ebf04-113">既定では、使用方法の詳細を一覧表示するときにこれらのフィールドは含まれません。</span><span class="sxs-lookup"><span data-stu-id="ebf04-113">By default, these fields are not included when listing usage details.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="ebf04-114">可能性があります usageDetails をフィルター処理するまたはで使用プロパティ/usageEnd (Utc 時間)、(Utc 時間) のプロパティ/usageStart、/リソース グループのプロパティ、プロパティ/instanceName プロパティ/instanceId。</span><span class="sxs-lookup"><span data-stu-id="ebf04-114">May be used to filter usageDetails by properties/usageEnd (Utc time), properties/usageStart (Utc time), properties/resourceGroup, properties/instanceName or properties/instanceId.</span></span> <span data-ttu-id="ebf04-115">フィルターをサポートしている eq"、"lt"、"gt"、"le"、"ge"、および 'および' です。</span><span class="sxs-lookup"><span data-stu-id="ebf04-115">The filter supports 'eq', 'lt', 'gt', 'le', 'ge', and 'and'.</span></span> <span data-ttu-id="ebf04-116">これはサポートされていません"ne"'または' または 'not' です。</span><span class="sxs-lookup"><span data-stu-id="ebf04-116">It does not currently support 'ne', 'or', or 'not'.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="ebf04-117">Skiptoken は前の操作には、部分的な結果が返された場合にのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-117">Skiptoken is only used if a previous operation returned a partial result.</span></span> <span data-ttu-id="ebf04-118">前の応答に nextLink 要素が含まれている場合 nextLink 要素の値には後続の呼び出しに使用する開始位置を指定する skiptoken パラメーターが含まれます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-118">If a previous response contains a nextLink element, the value of the nextLink element will include a skiptoken parameter that specifies a starting point to use for subsequent calls.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="ebf04-119">最新の N usageDetails する結果の数を制限するために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ebf04-119">May be used to limit the number of results to the most recent N usageDetails.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ebf04-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ebf04-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ebf04-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ebf04-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ebf04-122">請求期間使用して、スコープの使用方法の詳細を示します。</span><span class="sxs-lookup"><span data-stu-id="ebf04-122">Lists the usage details for a scope by billing period.</span></span> <span data-ttu-id="ebf04-123">使用方法の詳細のみ 2014 年 5 月 1 日またはそれ以降は、この API を使用して利用できます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-123">Usage details are available via this API only for May 1, 2014 or later.</span></span>
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponseException">
            <span data-ttu-id="ebf04-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ebf04-125">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-125">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ebf04-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ebf04-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>