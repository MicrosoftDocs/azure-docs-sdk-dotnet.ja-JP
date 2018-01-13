<Type Name="Profile" FullName="Microsoft.Azure.Management.TrafficManager.Models.Profile">
  <TypeSignature Language="C#" Value="public class Profile : Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Profile extends Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.Profile" />
  <TypeSignature Language="VB.NET" Value="Public Class Profile&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Profile = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.TrafficManager.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1ea6b-101">Traffic Manager プロファイルを表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-101">Class representing a Traffic Manager profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Profile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Profile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ea6b-102">プロファイル クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-102">Initializes a new instance of the Profile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Profile (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string profileStatus = null, string trafficRoutingMethod = null, Microsoft.Azure.Management.TrafficManager.Models.DnsConfig dnsConfig = null, Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig monitorConfig = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; endpoints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string profileStatus, string trafficRoutingMethod, class Microsoft.Azure.Management.TrafficManager.Models.DnsConfig dnsConfig, class Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig monitorConfig, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; endpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Profile.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.DnsConfig,Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig,System.Collections.Generic.IList{Microsoft.Azure.Management.TrafficManager.Models.Endpoint})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.Profile : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Microsoft.Azure.Management.TrafficManager.Models.DnsConfig * Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="new Microsoft.Azure.Management.TrafficManager.Models.Profile (id, name, type, location, tags, profileStatus, trafficRoutingMethod, dnsConfig, monitorConfig, endpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="profileStatus" Type="System.String" />
        <Parameter Name="trafficRoutingMethod" Type="System.String" />
        <Parameter Name="dnsConfig" Type="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig" />
        <Parameter Name="monitorConfig" Type="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig" />
        <Parameter Name="endpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1ea6b-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="1ea6b-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="1ea6b-104">リソース名</span><span class="sxs-lookup"><span data-stu-id="1ea6b-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="1ea6b-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="1ea6b-105">Resource type</span></span></param>
        <param name="location"><span data-ttu-id="1ea6b-106">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="1ea6b-106">Resource location</span></span></param>
        <param name="tags"><span data-ttu-id="1ea6b-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="1ea6b-107">Resource tags</span></span></param>
        <param name="profileStatus"><span data-ttu-id="1ea6b-108">取得または Traffic Manager プロファイルの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-108">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="1ea6b-109">指定できる値は、'Enabled' および '無効' には。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-109">Possible values are 'Enabled' and 'Disabled'.</span></span></param>
        <param name="trafficRoutingMethod"><span data-ttu-id="1ea6b-110">取得または Traffic Manager プロファイルのトラフィック ルーティング方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-110">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="1ea6b-111">使用可能な値は 'パフォーマンス'、'調整値'、'Priority' または '地理' です。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-111">Possible values are 'Performance', 'Weighted', 'Priority' or 'Geographic'.</span></span></param>
        <param name="dnsConfig"><span data-ttu-id="1ea6b-112">取得または Traffic Manager プロファイルの DNS 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-112">Gets or sets the DNS settings of the Traffic Manager profile.</span></span></param>
        <param name="monitorConfig"><span data-ttu-id="1ea6b-113">取得または設定、エンドポイントの Traffic Manager プロファイルの設定を監視します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-113">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span></param>
        <param name="endpoints"><span data-ttu-id="1ea6b-114">取得または Traffic Manager プロファイルでエンドポイントのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-114">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span></param>
        <summary>
            <span data-ttu-id="1ea6b-115">プロファイル クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-115">Initializes a new instance of the Profile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Models.DnsConfig DnsConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Models.DnsConfig DnsConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.DnsConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsConfig As DnsConfig" />
      <MemberSignature Language="F#" Value="member this.DnsConfig : Microsoft.Azure.Management.TrafficManager.Models.DnsConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.DnsConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.DnsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ea6b-116">取得または Traffic Manager プロファイルの DNS 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-116">Gets or sets the DNS settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; Endpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoints As IList(Of Endpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ea6b-117">取得または Traffic Manager プロファイルでエンドポイントのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-117">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig MonitorConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig MonitorConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.MonitorConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitorConfig As MonitorConfig" />
      <MemberSignature Language="F#" Value="member this.MonitorConfig : Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.MonitorConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.monitorConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ea6b-118">取得または設定、エンドポイントの Traffic Manager プロファイルの設定を監視します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-118">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProfileStatus">
      <MemberSignature Language="C#" Value="public string ProfileStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProfileStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.ProfileStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProfileStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProfileStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.ProfileStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.profileStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ea6b-119">取得または Traffic Manager プロファイルの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-119">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="1ea6b-120">指定できる値は、'Enabled' および '無効' には。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-120">Possible values are 'Enabled' and 'Disabled'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public string TrafficRoutingMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficRoutingMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.TrafficRoutingMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficRoutingMethod As String" />
      <MemberSignature Language="F#" Value="member this.TrafficRoutingMethod : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.TrafficRoutingMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trafficRoutingMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ea6b-121">取得または Traffic Manager プロファイルのトラフィック ルーティング方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-121">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="1ea6b-122">使用可能な値は 'パフォーマンス'、'調整値'、'Priority' または '地理' です。</span><span class="sxs-lookup"><span data-stu-id="1ea6b-122">Possible values are 'Performance', 'Weighted', 'Priority' or 'Geographic'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>