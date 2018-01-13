<Type Name="IUsageMetricsOperations" FullName="Microsoft.Azure.Management.Monitor.IUsageMetricsOperations">
  <TypeSignature Language="C#" Value="public interface IUsageMetricsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUsageMetricsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.IUsageMetricsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUsageMetricsOperations" />
  <TypeSignature Language="F#" Value="type IUsageMetricsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9650a-101">UsageMetricsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="9650a-101">UsageMetricsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceUri, string apiVersion, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceUri, string apiVersion, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.IUsageMetricsOperations.ListWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.UsageMetric},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt;" Usage="iUsageMetricsOperations.ListWithHttpMessagesAsync (resourceUri, apiVersion, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceUri">
            <span data-ttu-id="9650a-102">リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="9650a-102">The identifier of the resource.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="9650a-103">クライアント Api のバージョン。</span><span class="sxs-lookup"><span data-stu-id="9650a-103">Client Api Version.</span></span> <span data-ttu-id="9650a-104">注: このプロパティではありません、クライアントの呼び出しで明示的な場合があります、既定値はありません。</span><span class="sxs-lookup"><span data-stu-id="9650a-104">NOTE: This is not a client property, it must be explicit in the call and there is no default value.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9650a-105">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="9650a-105">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9650a-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9650a-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9650a-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9650a-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9650a-108">一覧操作では、リソースの使用状況メトリックが一覧表示します。&lt;br&gt;**警告**: この操作になります*廃止*次のリリースでします。</span><span class="sxs-lookup"><span data-stu-id="9650a-108">The List operation lists the usage metrics for the resource.&lt;br&gt;**WARNING**: This operation will be *deprecated* in the next release.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Models.ErrorResponseException">
            <span data-ttu-id="9650a-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9650a-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9650a-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9650a-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9650a-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9650a-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>