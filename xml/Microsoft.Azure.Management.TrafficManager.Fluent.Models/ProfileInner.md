<Type Name="ProfileInner" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner">
  <TypeSignature Language="C#" Value="public class ProfileInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProfileInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ProfileInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ProfileInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0edc4-101">Traffic Manager プロファイルを表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="0edc4-101">Class representing a Traffic Manager profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProfileInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0edc4-102">ProfileInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-102">Initializes a new instance of the ProfileInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProfileInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string profileStatus = null, string trafficRoutingMethod = null, Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig dnsConfig = null, Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig monitorConfig = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; endpoints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string profileStatus, string trafficRoutingMethod, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig dnsConfig, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig monitorConfig, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; endpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig,Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig,System.Collections.Generic.IList{Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig * Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner" Usage="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner (location, id, name, type, tags, profileStatus, trafficRoutingMethod, dnsConfig, monitorConfig, endpoints)" />
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
        <Parameter Name="profileStatus" Type="System.String" />
        <Parameter Name="trafficRoutingMethod" Type="System.String" />
        <Parameter Name="dnsConfig" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig" />
        <Parameter Name="monitorConfig" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig" />
        <Parameter Name="endpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="profileStatus"><span data-ttu-id="0edc4-103">取得または Traffic Manager プロファイルの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-103">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="0edc4-104">指定できる値は、'Enabled' および '無効' には。</span><span class="sxs-lookup"><span data-stu-id="0edc4-104">Possible values are 'Enabled' and 'Disabled'.</span></span></param>
        <param name="trafficRoutingMethod"><span data-ttu-id="0edc4-105">取得または Traffic Manager プロファイルのトラフィック ルーティング方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-105">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="0edc4-106">使用可能な値は 'パフォーマンス'、'調整値' または 'Priority' です。</span><span class="sxs-lookup"><span data-stu-id="0edc4-106">Possible values are 'Performance', 'Weighted', or 'Priority'.</span></span></param>
        <param name="dnsConfig"><span data-ttu-id="0edc4-107">取得または Traffic Manager プロファイルの DNS 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-107">Gets or sets the DNS settings of the Traffic Manager profile.</span></span></param>
        <param name="monitorConfig"><span data-ttu-id="0edc4-108">取得または設定、エンドポイントの Traffic Manager プロファイルの設定を監視します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-108">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span></param>
        <param name="endpoints"><span data-ttu-id="0edc4-109">取得または Traffic Manager プロファイルでエンドポイントのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-109">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span></param>
        <summary>
            <span data-ttu-id="0edc4-110">ProfileInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-110">Initializes a new instance of the ProfileInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig DnsConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig DnsConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.DnsConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsConfig As DnsConfig" />
      <MemberSignature Language="F#" Value="member this.DnsConfig : Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.DnsConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0edc4-111">取得または Traffic Manager プロファイルの DNS 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-111">Gets or sets the DNS settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; Endpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoints As IList(Of EndpointInner)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0edc4-112">取得または Traffic Manager プロファイルでエンドポイントのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-112">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig MonitorConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig MonitorConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.MonitorConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitorConfig As MonitorConfig" />
      <MemberSignature Language="F#" Value="member this.MonitorConfig : Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.MonitorConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.monitorConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0edc4-113">取得または設定、エンドポイントの Traffic Manager プロファイルの設定を監視します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-113">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProfileStatus">
      <MemberSignature Language="C#" Value="public string ProfileStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProfileStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.ProfileStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProfileStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProfileStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.ProfileStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="0edc4-114">取得または Traffic Manager プロファイルの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-114">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="0edc4-115">指定できる値は、'Enabled' および '無効' には。</span><span class="sxs-lookup"><span data-stu-id="0edc4-115">Possible values are 'Enabled' and 'Disabled'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public string TrafficRoutingMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficRoutingMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.TrafficRoutingMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficRoutingMethod As String" />
      <MemberSignature Language="F#" Value="member this.TrafficRoutingMethod : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.TrafficRoutingMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="0edc4-116">取得または Traffic Manager プロファイルのトラフィック ルーティング方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="0edc4-116">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="0edc4-117">使用可能な値は 'パフォーマンス'、'調整値' または 'Priority' です。</span><span class="sxs-lookup"><span data-stu-id="0edc4-117">Possible values are 'Performance', 'Weighted', or 'Priority'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>