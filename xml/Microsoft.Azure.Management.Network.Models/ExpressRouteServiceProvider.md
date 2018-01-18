<Type Name="ExpressRouteServiceProvider" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider">
  <TypeSignature Language="C#" Value="public class ExpressRouteServiceProvider : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteServiceProvider extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteServiceProvider&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ExpressRouteServiceProvider = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b87e3-101">ExpressRouteResourceProvider オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="b87e3-101">A ExpressRouteResourceProvider object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteServiceProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b87e3-102">ExpressRouteServiceProvider クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-102">Initializes a new instance of the ExpressRouteServiceProvider class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteServiceProvider (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;string&gt; peeringLocations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; bandwidthsOffered = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;string&gt; peeringLocations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; bandwidthsOffered, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional peeringLocations As IList(Of String) = null, Optional bandwidthsOffered As IList(Of ExpressRouteServiceProviderBandwidthsOffered) = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider (id, name, type, location, tags, peeringLocations, bandwidthsOffered, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="peeringLocations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="bandwidthsOffered" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="b87e3-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="b87e3-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="b87e3-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="b87e3-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="b87e3-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="b87e3-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="b87e3-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="b87e3-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="b87e3-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="b87e3-107">Resource tags.</span></span></param>
        <param name="peeringLocations"><span data-ttu-id="b87e3-108">ピアリングの場所の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-108">Get a list of peering locations.</span></span></param>
        <param name="bandwidthsOffered"><span data-ttu-id="b87e3-109">提供される帯域幅を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-109">Gets bandwidths offered.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="b87e3-110">リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-110">Gets the provisioning state of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="b87e3-111">ExpressRouteServiceProvider クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-111">Initializes a new instance of the ExpressRouteServiceProvider class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BandwidthsOffered">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; BandwidthsOffered { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; BandwidthsOffered" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.BandwidthsOffered" />
      <MemberSignature Language="VB.NET" Value="Public Property BandwidthsOffered As IList(Of ExpressRouteServiceProviderBandwidthsOffered)" />
      <MemberSignature Language="F#" Value="member this.BandwidthsOffered : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.BandwidthsOffered" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bandwidthsOffered")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProviderBandwidthsOffered&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b87e3-112">提供される帯域幅を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-112">Gets bandwidths offered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeeringLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PeeringLocations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PeeringLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.PeeringLocations" />
      <MemberSignature Language="VB.NET" Value="Public Property PeeringLocations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PeeringLocations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.PeeringLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peeringLocations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b87e3-113">取得または設定は、ピアリングの場所の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-113">Gets or sets get a list of peering locations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b87e3-114">リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87e3-114">Gets the provisioning state of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>