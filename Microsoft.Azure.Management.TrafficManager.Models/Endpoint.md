<Type Name="Endpoint" FullName="Microsoft.Azure.Management.TrafficManager.Models.Endpoint">
  <TypeSignature Language="C#" Value="public class Endpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Endpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class Endpoint" />
  <TypeSignature Language="F#" Value="type Endpoint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Traffic Manager エンドポイントを表すクラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Endpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Endpoint クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Endpoint (string id = null, string name = null, string type = null, string targetResourceId = null, string target = null, string endpointStatus = null, Nullable&lt;long&gt; weight = null, Nullable&lt;long&gt; priority = null, string endpointLocation = null, string endpointMonitorStatus = null, Nullable&lt;long&gt; minChildEndpoints = null, System.Collections.Generic.IList&lt;string&gt; geoMapping = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string targetResourceId, string target, string endpointStatus, valuetype System.Nullable`1&lt;int64&gt; weight, valuetype System.Nullable`1&lt;int64&gt; priority, string endpointLocation, string endpointMonitorStatus, valuetype System.Nullable`1&lt;int64&gt; minChildEndpoints, class System.Collections.Generic.IList`1&lt;string&gt; geoMapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.Int64},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional targetResourceId As String = null, Optional target As String = null, Optional endpointStatus As String = null, Optional weight As Nullable(Of Long) = null, Optional priority As Nullable(Of Long) = null, Optional endpointLocation As String = null, Optional endpointMonitorStatus As String = null, Optional minChildEndpoints As Nullable(Of Long) = null, Optional geoMapping As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.Endpoint : string * string * string * string * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * string * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="new Microsoft.Azure.Management.TrafficManager.Models.Endpoint (id, name, type, targetResourceId, target, endpointStatus, weight, priority, endpointLocation, endpointMonitorStatus, minChildEndpoints, geoMapping)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="endpointStatus" Type="System.String" />
        <Parameter Name="weight" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="endpointLocation" Type="System.String" />
        <Parameter Name="endpointMonitorStatus" Type="System.String" />
        <Parameter Name="minChildEndpoints" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="geoMapping" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">取得または Traffic Manager エンドポイントの ID を設定します。</param>
        <param name="name">取得または Traffic Manager エンドポイントの名前を設定します。</param>
        <param name="type">取得または Traffic Manager エンドポイントのエンドポイントの種類を設定します。</param>
        <param name="targetResourceId">取得または設定、Azure リソースの URI、エンドポイントのです。  種類 'ExternalEndpoints' のエンドポイントには適用されません。</param>
        <param name="target">取得またはエンドポイントの完全修飾 DNS 名を設定します。  Traffic Manager は、このエンドポイントにトラフィックをダイレクトする DNS 応答でこの値を返します。</param>
        <param name="endpointStatus">取得またはエンドポイントの状態を設定.  エンドポイントが有効になっている場合、エンドポイントの正常性の検出され、トラフィック ルーティング方法に含まれます。  指定できる値は、'Enabled' および '無効' には。</param>
        <param name="weight">取得または '調整値' トラフィック ルーティング方法を使用する場合に、このエンドポイントの重みを設定します。 使用可能な値は、1 ~ 1000 です。</param>
        <param name="priority">取得または、'Priority' トラフィック ルーティング方法を使用する場合は、このエンドポイントの優先順位を設定します。 使用可能な値は、1 ~ 1000、値と低い値が高い優先順位を表します。 これは省略可能なパラメーターです。  指定する場合、すべてのエンドポイントで指定する必要があり、2 つのエンドポイントが同じ優先度の値を共有できます。</param>
        <param name="endpointLocation">'パフォーマンス' トラフィック ルーティング方法を使用する場合は、外部または入れ子にされたエンドポイントの場所を指定します。</param>
        <param name="endpointMonitorStatus">取得またはエンドポイントの監視の状態を設定します。</param>
        <param name="minChildEndpoints">取得または使用できると見なされるに親プロファイルの順序で子プロファイルで使用する必要があるエンドポイントの最小数を設定します。 型 'NestedEndpoints' のエンドポイントにのみ適用されます。</param>
        <param name="geoMapping">取得または '地理' トラフィック ルーティング方法を使用する場合は、このエンドポイントにマップされている国または地域の一覧を設定します。 可能な値の完全な一覧については、Traffic Manager 地理のマニュアルを参照してください。</param>
        <summary>
            Endpoint クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointLocation">
      <MemberSignature Language="C#" Value="public string EndpointLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointLocation As String" />
      <MemberSignature Language="F#" Value="member this.EndpointLocation : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、外部の場所を指定するか、'パフォーマンス' を使用する場合、入れ子になったエンドポイント トラフィック ルーティング方法。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointMonitorStatus">
      <MemberSignature Language="C#" Value="public string EndpointMonitorStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointMonitorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointMonitorStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointMonitorStatus As String" />
      <MemberSignature Language="F#" Value="member this.EndpointMonitorStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointMonitorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointMonitorStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンドポイントの監視の状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointStatus">
      <MemberSignature Language="C#" Value="public string EndpointStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointStatus As String" />
      <MemberSignature Language="F#" Value="member this.EndpointStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンドポイントの状態を設定.  エンドポイントが有効になっている場合、エンドポイントの正常性の検出され、トラフィック ルーティング方法に含まれます。  指定できる値は、'Enabled' および '無効' には。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoMapping">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GeoMapping { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; GeoMapping" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.GeoMapping" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoMapping As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.GeoMapping : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.GeoMapping" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoMapping")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または '地理' トラフィック ルーティング方法を使用する場合は、このエンドポイントにマップされている国または地域の一覧を設定します。 可能な値の完全な一覧については、Traffic Manager 地理のマニュアルを参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager エンドポイントの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinChildEndpoints">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinChildEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinChildEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.MinChildEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property MinChildEndpoints As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinChildEndpoints : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.MinChildEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minChildEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用できると見なされるに親プロファイルの順序で子プロファイルで使用する必要があるエンドポイントの最小数を設定します。 型 'NestedEndpoints' のエンドポイントにのみ適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager エンドポイントの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、'Priority' トラフィック ルーティング方法を使用する場合は、このエンドポイントの優先順位を設定します。 使用可能な値は、1 ~ 1000、値と低い値が高い優先順位を表します。 これは省略可能なパラメーターです。  指定する場合、すべてのエンドポイントで指定する必要があり、2 つのエンドポイントが同じ優先度の値を共有できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンドポイントの完全修飾 DNS 名を設定します。  Traffic Manager は、このエンドポイントにトラフィックをダイレクトする DNS 応答でこの値を返します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、Azure リソースの URI、エンドポイントのです。  種類 'ExternalEndpoints' のエンドポイントには適用されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager エンドポイントのエンドポイントの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Weight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Weight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Weight" />
      <MemberSignature Language="VB.NET" Value="Public Property Weight As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Weight : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.weight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または '調整値' トラフィック ルーティング方法を使用する場合に、このエンドポイントの重みを設定します。 使用可能な値は、1 ~ 1000 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>