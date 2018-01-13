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
            MetricsOperations 操作です。
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
            リソースの識別子。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="timespan">
            クエリの timespan です。 これは、次の形式 'startDateTime_ISO/endDateTime_ISO' の文字列です。
            </param>
        <param name="interval">
            クエリの間隔 (つまり timegrain)。
            </param>
        <param name="metric">
            取得するメトリックの名前。
            </param>
        <param name="aggregation">
            集計の種類 (コンマ区切り) の一覧を取得します。
            </param>
        <param name="resultType">
            収集されたデータのセットが減少します。 許可されている構文は、操作によって異なります。 詳細については、操作の説明を参照してください。
            使用可能な値が含まれます: 'データ'、'Metadata'
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            **リソースのメトリックの値を一覧表示**です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Models.ErrorResponseException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>