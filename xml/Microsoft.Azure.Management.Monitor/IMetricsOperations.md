<Type Name="IMetricsOperations" FullName="Microsoft.Azure.Management.Monitor.IMetricsOperations">
  <TypeSignature Language="C#" Value="public interface IMetricsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMetricsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.IMetricsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMetricsOperations" />
  <TypeSignature Language="F#" Value="type IMetricsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b63ee-101">MetricsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b63ee-101">MetricsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt; ListWithHttpMessagesAsync (string resourceUri, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery = null, string timespan = null, Nullable&lt;TimeSpan&gt; interval = null, string metric = null, string aggregation = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt; ListWithHttpMessagesAsync(string resourceUri, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery, string timespan, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval, string metric, string aggregation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.IMetricsOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.MetadataValue},System.String,System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Models.ResultType},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; * string * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt;" Usage="iMetricsOperations.ListWithHttpMessagesAsync (resourceUri, odataQuery, timespan, interval, metric, aggregation, resultType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;" />
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="metric" Type="System.String" />
        <Parameter Name="aggregation" Type="System.String" />
        <Parameter Name="resultType" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceUri">
            <span data-ttu-id="b63ee-102">リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="b63ee-102">The identifier of the resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="b63ee-103">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b63ee-103">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="timespan">
            <span data-ttu-id="b63ee-104">クエリの timespan です。</span><span class="sxs-lookup"><span data-stu-id="b63ee-104">The timespan of the query.</span></span> <span data-ttu-id="b63ee-105">これは、次の形式 'startDateTime_ISO/endDateTime_ISO' の文字列です。</span><span class="sxs-lookup"><span data-stu-id="b63ee-105">It is a string with the following format 'startDateTime_ISO/endDateTime_ISO'.</span></span>
            </param>
        <param name="interval">
            <span data-ttu-id="b63ee-106">クエリの間隔 (つまり timegrain)。</span><span class="sxs-lookup"><span data-stu-id="b63ee-106">The interval (i.e. timegrain) of the query.</span></span>
            </param>
        <param name="metric">
            <span data-ttu-id="b63ee-107">取得するメトリックの名前。</span><span class="sxs-lookup"><span data-stu-id="b63ee-107">The name of the metric to retrieve.</span></span>
            </param>
        <param name="aggregation">
            <span data-ttu-id="b63ee-108">集計の種類 (コンマ区切り) の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b63ee-108">The list of aggregation types (comma separated) to retrieve.</span></span>
            </param>
        <param name="resultType">
            <span data-ttu-id="b63ee-109">収集されたデータのセットが減少します。</span><span class="sxs-lookup"><span data-stu-id="b63ee-109">Reduces the set of data collected.</span></span> <span data-ttu-id="b63ee-110">許可されている構文は、操作によって異なります。</span><span class="sxs-lookup"><span data-stu-id="b63ee-110">The syntax allowed depends on the operation.</span></span> <span data-ttu-id="b63ee-111">詳細については、操作の説明を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b63ee-111">See the operation's description for details.</span></span>
            <span data-ttu-id="b63ee-112">使用可能な値が含まれます: 'データ'、'Metadata'</span><span class="sxs-lookup"><span data-stu-id="b63ee-112">Possible values include: 'Data', 'Metadata'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b63ee-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b63ee-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b63ee-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b63ee-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b63ee-115">**リソースのメトリックの値を一覧表示**です。</span><span class="sxs-lookup"><span data-stu-id="b63ee-115">**Lists the metric values for a resource**.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Models.ErrorResponseException">
            <span data-ttu-id="b63ee-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b63ee-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b63ee-117">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b63ee-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b63ee-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b63ee-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>