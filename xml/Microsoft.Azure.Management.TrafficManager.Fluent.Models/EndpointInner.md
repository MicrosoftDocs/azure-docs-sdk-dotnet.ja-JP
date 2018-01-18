<Type Name="EndpointInner" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner">
  <TypeSignature Language="C#" Value="public class EndpointInner : Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProxyResourceInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EndpointInner extends Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProxyResourceInner" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
  <TypeSignature Language="VB.NET" Value="Public Class EndpointInner&#xA;Inherits ProxyResourceInner" />
  <TypeSignature Language="F#" Value="type EndpointInner = class&#xA;    inherit ProxyResourceInner" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProxyResourceInner</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="cab13-101">Traffic Manager エンドポイントを表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="cab13-101">Class representing a Traffic Manager endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cab13-102">EndpointInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cab13-102">Initializes a new instance of the EndpointInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string targetResourceId = null, string target = null, string endpointStatus = null, Nullable&lt;long&gt; weight = null, Nullable&lt;long&gt; priority = null, string endpointLocation = null, string endpointMonitorStatus = null, Nullable&lt;long&gt; minChildEndpoints = null, System.Collections.Generic.IList&lt;string&gt; geoMapping = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string targetResourceId, string target, string endpointStatus, valuetype System.Nullable`1&lt;int64&gt; weight, valuetype System.Nullable`1&lt;int64&gt; priority, string endpointLocation, string endpointMonitorStatus, valuetype System.Nullable`1&lt;int64&gt; minChildEndpoints, class System.Collections.Generic.IList`1&lt;string&gt; geoMapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.Int64},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional targetResourceId As String = null, Optional target As String = null, Optional endpointStatus As String = null, Optional weight As Nullable(Of Long) = null, Optional priority As Nullable(Of Long) = null, Optional endpointLocation As String = null, Optional endpointMonitorStatus As String = null, Optional minChildEndpoints As Nullable(Of Long) = null, Optional geoMapping As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * string * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" Usage="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner (location, id, name, type, tags, targetResourceId, target, endpointStatus, weight, priority, endpointLocation, endpointMonitorStatus, minChildEndpoints, geoMapping)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
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
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="targetResourceId">To be added.</param>
        <param name="target">To be added.</param>
        <param name="endpointStatus">To be added.</param>
        <param name="weight">To be added.</param>
        <param name="priority">To be added.</param>
        <param name="endpointLocation">To be added.</param>
        <param name="endpointMonitorStatus">To be added.</param>
        <param name="minChildEndpoints">To be added.</param>
        <param name="geoMapping">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointLocation">
      <MemberSignature Language="C#" Value="public string EndpointLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.EndpointLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointLocation As String" />
      <MemberSignature Language="F#" Value="member this.EndpointLocation : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.EndpointLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-103">取得または設定は、外部の場所を指定するか、'パフォーマンス' を使用する場合、入れ子になったエンドポイント トラフィック ルーティング方法。</span><span class="sxs-lookup"><span data-stu-id="cab13-103">Gets or sets specifies the location of the external or nested endpoints when using the ‘Performance’ traffic routing method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointMonitorStatus">
      <MemberSignature Language="C#" Value="public string EndpointMonitorStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointMonitorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.EndpointMonitorStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointMonitorStatus As String" />
      <MemberSignature Language="F#" Value="member this.EndpointMonitorStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.EndpointMonitorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-104">取得またはエンドポイントの監視の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="cab13-104">Gets or sets the monitoring status of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointStatus">
      <MemberSignature Language="C#" Value="public string EndpointStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.EndpointStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointStatus As String" />
      <MemberSignature Language="F#" Value="member this.EndpointStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.EndpointStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-105">取得またはエンドポイントの状態を設定.</span><span class="sxs-lookup"><span data-stu-id="cab13-105">Gets or sets the status of the endpoint..</span></span>  <span data-ttu-id="cab13-106">エンドポイントが有効になっている場合、エンドポイントの正常性の検出され、トラフィック ルーティング方法に含まれます。</span><span class="sxs-lookup"><span data-stu-id="cab13-106">If the endpoint is Enabled, it is probed for endpoint health and is included in the traffic routing method.</span></span>  <span data-ttu-id="cab13-107">指定できる値は、'Enabled' および '無効' には。</span><span class="sxs-lookup"><span data-stu-id="cab13-107">Possible values are 'Enabled' and 'Disabled'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoMapping">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GeoMapping { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; GeoMapping" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.GeoMapping" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoMapping As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.GeoMapping : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.GeoMapping" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinChildEndpoints">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinChildEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinChildEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.MinChildEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property MinChildEndpoints As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinChildEndpoints : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.MinChildEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-108">取得または使用できると見なされるに親プロファイルの順序で子プロファイルで使用する必要があるエンドポイントの最小数を設定します。</span><span class="sxs-lookup"><span data-stu-id="cab13-108">Gets or sets the minimum number of endpoints that must be available in the child profile in order for the parent profile to be considered available.</span></span> <span data-ttu-id="cab13-109">型 'NestedEndpoints' のエンドポイントにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="cab13-109">Only applicable to endpoint of type 'NestedEndpoints'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-110">取得または、'Priority' トラフィック ルーティング方法を使用する場合は、このエンドポイントの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="cab13-110">Gets or sets the priority of this endpoint when using the ‘Priority’ traffic routing method.</span></span> <span data-ttu-id="cab13-111">使用可能な値は、1 ~ 1000、値と低い値が高い優先順位を表します。</span><span class="sxs-lookup"><span data-stu-id="cab13-111">Possible values are from 1 to 1000, lower values represent higher priority.</span></span> <span data-ttu-id="cab13-112">これは省略可能なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cab13-112">This is an optional parameter.</span></span>  <span data-ttu-id="cab13-113">指定する場合、すべてのエンドポイントで指定する必要があり、2 つのエンドポイントが同じ優先度の値を共有できます。</span><span class="sxs-lookup"><span data-stu-id="cab13-113">If specified, it must be specified on all endpoints, and no two endpoints can share the same priority value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-114">取得またはエンドポイントの完全修飾 DNS 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="cab13-114">Gets or sets the fully-qualified DNS name of the endpoint.</span></span>  <span data-ttu-id="cab13-115">Traffic Manager は、このエンドポイントにトラフィックをダイレクトする DNS 応答でこの値を返します。</span><span class="sxs-lookup"><span data-stu-id="cab13-115">Traffic Manager returns this value in DNS responses to direct traffic to this endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-116">取得または設定、Azure リソースの URI、エンドポイントのです。</span><span class="sxs-lookup"><span data-stu-id="cab13-116">Gets or sets the Azure Resource URI of the of the endpoint.</span></span>  <span data-ttu-id="cab13-117">種類 'ExternalEndpoints' のエンドポイントには適用されません。</span><span class="sxs-lookup"><span data-stu-id="cab13-117">Not applicable to endpoints of type 'ExternalEndpoints'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Weight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Weight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.Weight" />
      <MemberSignature Language="VB.NET" Value="Public Property Weight As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Weight : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="cab13-118">取得または '調整値' トラフィック ルーティング方法を使用する場合に、このエンドポイントの重みを設定します。</span><span class="sxs-lookup"><span data-stu-id="cab13-118">Gets or sets the weight of this endpoint when using the 'Weighted' traffic routing method.</span></span> <span data-ttu-id="cab13-119">使用可能な値は、1 ~ 1000 です。</span><span class="sxs-lookup"><span data-stu-id="cab13-119">Possible values are from 1 to 1000.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>