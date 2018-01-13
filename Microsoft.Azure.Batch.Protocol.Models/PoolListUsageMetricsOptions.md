<Type Name="PoolListUsageMetricsOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions">
  <TypeSignature Language="C#" Value="public class PoolListUsageMetricsOptions : Microsoft.Azure.Batch.Protocol.Models.IODataFilter, Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolListUsageMetricsOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IODataFilter, class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolListUsageMetricsOptions&#xA;Implements IODataFilter, ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type PoolListUsageMetricsOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions&#xA;    interface IODataFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IODataFilter</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ListUsageMetrics 操作に追加のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolListUsageMetricsOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PoolListUsageMetricsOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolListUsageMetricsOptions (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string filter = null, Nullable&lt;int&gt; maxResults = null, Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string filter, valuetype System.Nullable`1&lt;int32&gt; maxResults, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional filter As String = null, Optional maxResults As Nullable(Of Integer) = null, Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions (startTime, endTime, filter, maxResults, timeout, clientRequestId, returnClientRequestId, ocpDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="returnClientRequestId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime">元のメトリックを含める最も早い時刻。 これは、現在の時刻より前に少なくとも 2.5 時間でなければなりません。 既定値は現在使用可能な最後の集計間隔の開始時刻を指定しない場合。</param>
        <param name="endTime">元のメトリックを含める最も遅い時刻。 これは、現在の時刻より前に 2 時間以上でなければなりません。
            既定値は現在使用可能な最後の集計間隔の終了時刻を指定しない場合。</param>
        <param name="filter">OData $filter 句の場合です。 このフィルターを構築する方法については、https://docs.microsoft.com/en-us/rest/api/batchservice/odata-filters-in-batch#list-account-usage-metrics を参照してください。</param>
        <param name="maxResults">応答で返されるアイテムの最大数。 最大 1000 の結果が返されます。</param>
        <param name="timeout">最大時間を秒単位で、要求の処理に、サーバーが費やすことができます。 既定値は 30 秒です。</param>
        <param name="clientRequestId">例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式で、呼び出し元によって生成された要求 id-4 CD 3-8152-34347DC9F2B0 です。</param>
        <param name="returnClientRequestId">サーバーが応答でクライアント要求 id を返すかどうか。</param>
        <param name="ocpDate">要求が発行された時刻。 クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。</param>
        <summary>
            PoolListUsageMetricsOptions クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式では呼び出し元によって生成された要求 id が設定を取得または -4 CD 3-8152-34347DC9F2B0 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または元のメトリックを含める最も遅い時刻を設定します。 これは、現在の時刻より前に 2 時間以上でなければなりません。 既定値は現在使用可能な最後の集計間隔の終了時刻を指定しない場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.Filter" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IODataFilter.Filter</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OData $filter 句を設定します。 このフィルターを構築する方法については、https://docs.microsoft.com/en-us/rest/api/batchservice/odata-filters-in-batch#list-account-usage-metrics を参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または応答で返されるアイテムの最大数を設定します。
            最大 1000 の結果が返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.OcpDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求が発行された時刻を設定します。 クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.ReturnClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ReturnClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサーバーが応答でクライアント要求 id を返すかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または元のメトリックを含める最も早い時刻を設定します。 これは、現在の時刻より前に少なくとも 2.5 時間でなければなりません。 既定値は現在使用可能な最後の集計間隔の開始時刻を指定しない場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions.Timeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions.Timeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の最大時間 (秒)、要求の処理に、サーバーが費やすことができます。 既定値は 30 秒です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>