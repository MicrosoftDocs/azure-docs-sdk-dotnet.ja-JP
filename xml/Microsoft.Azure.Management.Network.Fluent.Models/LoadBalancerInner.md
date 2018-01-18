<Type Name="LoadBalancerInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner">
  <TypeSignature Language="C#" Value="public class LoadBalancerInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LoadBalancerInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner" />
  <TypeSignature Language="VB.NET" Value="Public Class LoadBalancerInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type LoadBalancerInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="97be7-101">ロード バランサー リソース</span><span class="sxs-lookup"><span data-stu-id="97be7-101">LoadBalancer resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancerInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="97be7-102">LoadBalancerInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97be7-102">Initializes a new instance of the LoadBalancerInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancerInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku sku = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; frontendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; backendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; loadBalancingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; probes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; inboundNatRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; inboundNatPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; outboundNatRules = null, string resourceGuid = null, string provisioningState = null, string etag = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku sku, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; frontendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; backendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; loadBalancingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; probes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; inboundNatRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; inboundNatPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; outboundNatRules, string resourceGuid, string provisioningState, string etag, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner},System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As LoadBalancerSku = null, Optional frontendIPConfigurations As IList(Of FrontendIPConfigurationInner) = null, Optional backendAddressPools As IList(Of BackendAddressPoolInner) = null, Optional loadBalancingRules As IList(Of LoadBalancingRuleInner) = null, Optional probes As IList(Of ProbeInner) = null, Optional inboundNatRules As IList(Of InboundNatRuleInner) = null, Optional inboundNatPools As IList(Of InboundNatPoolInner) = null, Optional outboundNatRules As IList(Of OutboundNatRuleInner) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null, Optional zones As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner (location, id, name, type, tags, sku, frontendIPConfigurations, backendAddressPools, loadBalancingRules, probes, inboundNatRules, inboundNatPools, outboundNatRules, resourceGuid, provisioningState, etag, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt;" />
        <Parameter Name="backendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt;" />
        <Parameter Name="probes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;" />
        <Parameter Name="inboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt;" />
        <Parameter Name="inboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt;" />
        <Parameter Name="outboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="sku">To be added.</param>
        <param name="frontendIPConfigurations">To be added.</param>
        <param name="backendAddressPools">To be added.</param>
        <param name="loadBalancingRules">To be added.</param>
        <param name="probes">To be added.</param>
        <param name="inboundNatRules">To be added.</param>
        <param name="inboundNatPools">To be added.</param>
        <param name="outboundNatRules">To be added.</param>
        <param name="resourceGuid">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="etag">To be added.</param>
        <param name="zones">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; BackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; BackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.BackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPools As IList(Of BackendAddressPoolInner)" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.BackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-103">取得または設定のロード バランサーによって使用されるバックエンド アドレス プールのコレクション</span><span class="sxs-lookup"><span data-stu-id="97be7-103">Gets or sets collection of backend address pools used by a load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-104">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="97be7-104">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of FrontendIPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.FrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-105">取得または設定するフロント エンド ロード バランサーに使用する ip アドレスを表すオブジェクト</span><span class="sxs-lookup"><span data-stu-id="97be7-105">Gets or sets object representing the frontend IPs to be used for the load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; InboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatPools As IList(Of InboundNatPoolInner)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-106">取得または設定は、ロード バランサーに関連付けられている Nic で 1 台のバックエンド ポートへの着信 NAT を外部ポート範囲を定義します。</span><span class="sxs-lookup"><span data-stu-id="97be7-106">Gets or sets defines an external port range for inbound NAT to a single backend port on NICs associated with a load balancer.</span></span>
            <span data-ttu-id="97be7-107">この範囲から外部ポートを使用するロード バランサーに関連付けられている各 NIC の受信 NAT 規則が自動的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="97be7-107">Inbound NAT rules are created automatically for each NIC associated with the Load Balancer using an external port from this range.</span></span>
            <span data-ttu-id="97be7-108">受信 Nat 規則の定義で相互に排他的では、ロード バランサーの着信 NAT プールを定義します。</span><span class="sxs-lookup"><span data-stu-id="97be7-108">Defining an Inbound NAT pool on your Load Balancer is mutually exclusive with defining inbound Nat rules.</span></span> <span data-ttu-id="97be7-109">着信 NAT プールは、仮想マシン スケール セットから参照されます。</span><span class="sxs-lookup"><span data-stu-id="97be7-109">Inbound NAT pools are referenced from virtual machine scale sets.</span></span> <span data-ttu-id="97be7-110">個々 の仮想マシンに関連付けられている Nic には、受信の NAT プールを参照できません。</span><span class="sxs-lookup"><span data-stu-id="97be7-110">NICs that are associated with individual virtual machines cannot reference an inbound NAT pool.</span></span> <span data-ttu-id="97be7-111">個々 の受信 NAT 規則を参照する必要があります。</span><span class="sxs-lookup"><span data-stu-id="97be7-111">They have to reference individual inbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; InboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; InboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatRules As IList(Of InboundNatRuleInner)" />
      <MemberSignature Language="F#" Value="member this.InboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-112">取得またはロード バランサーによって使用される受信の NAT 規則のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="97be7-112">Gets or sets collection of inbound NAT Rules used by a load balancer.</span></span> <span data-ttu-id="97be7-113">ロード バランサーの受信 NAT 規則を定義するは、着信 NAT プールの定義で相互に排他的です。</span><span class="sxs-lookup"><span data-stu-id="97be7-113">Defining inbound NAT rules on your load balancer is mutually exclusive with defining an inbound NAT pool.</span></span> <span data-ttu-id="97be7-114">着信 NAT プールは、仮想マシン スケール セットから参照されます。</span><span class="sxs-lookup"><span data-stu-id="97be7-114">Inbound NAT pools are referenced from virtual machine scale sets.</span></span> <span data-ttu-id="97be7-115">個々 の仮想マシンに関連付けられている Nic には、着信 NAT プールを参照できません。</span><span class="sxs-lookup"><span data-stu-id="97be7-115">NICs that are associated with individual virtual machines cannot reference an Inbound NAT pool.</span></span> <span data-ttu-id="97be7-116">個々 の受信 NAT 規則を参照する必要があります。</span><span class="sxs-lookup"><span data-stu-id="97be7-116">They have to reference individual inbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; LoadBalancingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancingRules As IList(Of LoadBalancingRuleInner)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-117">取得または負荷分散の規則の取得を表すオブジェクト コレクションのプロビジョニングを設定</span><span class="sxs-lookup"><span data-stu-id="97be7-117">Gets or sets object collection representing the load balancing rules Gets the provisioning</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; OutboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; OutboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.OutboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property OutboundNatRules As IList(Of OutboundNatRuleInner)" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.OutboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-118">取得または送信 NAT 規則を設定します。</span><span class="sxs-lookup"><span data-stu-id="97be7-118">Gets or sets the outbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; Probes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; Probes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Probes" />
      <MemberSignature Language="VB.NET" Value="Public Property Probes As IList(Of ProbeInner)" />
      <MemberSignature Language="F#" Value="member this.Probes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Probes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-119">取得または設定のロード バランサーで使用されるプローブ オブジェクトのコレクション</span><span class="sxs-lookup"><span data-stu-id="97be7-119">Gets or sets collection of probe objects used in the load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="97be7-120">パブリック Ip リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="97be7-120">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="97be7-121">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="97be7-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="97be7-122">取得またはリソース GUID、ロード バランサーのリソースのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="97be7-122">Gets or sets the resource GUID property of the load balancer resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As LoadBalancerSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
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
  </Members>
</Type>