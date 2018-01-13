<Type Name="MetricsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MetricsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MetricsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MetricsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MetricsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            MetricsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Models.Response List (this Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery = null, string timespan = null, Nullable&lt;TimeSpan&gt; interval = null, string metric = null, string aggregation = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Models.Response List(class Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery, string timespan, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval, string metric, string aggregation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IMetricsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.MetadataValue},System.String,System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Models.ResultType})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IMetricsOperations, resourceUri As String, Optional odataQuery As ODataQuery(Of MetadataValue) = null, Optional timespan As String = null, Optional interval As Nullable(Of TimeSpan) = null, Optional metric As String = null, Optional aggregation As String = null, Optional resultType As Nullable(Of ResultType) = null) As Response" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IMetricsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; * string * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.Response" Usage="Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.List (operations, resourceUri, odataQuery, timespan, interval, metric, aggregation, resultType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.Response</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;" />
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="metric" Type="System.String" />
        <Parameter Name="aggregation" Type="System.String" />
        <Parameter Name="resultType" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
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
            収集されたデータのセットが減少します。 許可されている構文は、操作によって異なります。 詳細については、操作の説明を参照してください。 使用可能な値が含まれます: 'データ'、'Metadata'
            </param>
        <summary>
            **リソースのメトリックの値を一覧表示**です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery = null, string timespan = null, Nullable&lt;TimeSpan&gt; interval = null, string metric = null, string aggregation = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Models.Response&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery, string timespan, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval, string metric, string aggregation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IMetricsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.MetadataValue},System.String,System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Models.ResultType},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IMetricsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; * string * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;" Usage="Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.ListAsync (operations, resourceUri, odataQuery, timespan, interval, metric, aggregation, resultType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;" />
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="metric" Type="System.String" />
        <Parameter Name="aggregation" Type="System.String" />
        <Parameter Name="resultType" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
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
            収集されたデータのセットが減少します。 許可されている構文は、操作によって異なります。 詳細については、操作の説明を参照してください。 使用可能な値が含まれます: 'データ'、'Metadata'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            **リソースのメトリックの値を一覧表示**です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>