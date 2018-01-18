<Type Name="ExpressRouteCircuitPeering" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitPeering : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitPeering extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitPeering&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitPeering = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="02aae-101">ピアリング ExpressRouteCircuit リソースでします。</span><span class="sxs-lookup"><span data-stu-id="02aae-101">Peering in an ExpressRouteCircuit resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeering ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.#ctor" />
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
            <span data-ttu-id="02aae-102">ExpressRouteCircuitPeering クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02aae-102">Initializes a new instance of the ExpressRouteCircuitPeering class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeering (string id = null, string peeringType = null, string state = null, Nullable&lt;int&gt; azureASN = null, Nullable&lt;int&gt; peerASN = null, string primaryPeerAddressPrefix = null, string secondaryPeerAddressPrefix = null, string primaryAzurePort = null, string secondaryAzurePort = null, string sharedKey = null, Nullable&lt;int&gt; vlanId = null, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig = null, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats stats = null, string provisioningState = null, string gatewayManagerEtag = null, string lastModifiedBy = null, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilter = null, Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig ipv6PeeringConfig = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string peeringType, string state, valuetype System.Nullable`1&lt;int32&gt; azureASN, valuetype System.Nullable`1&lt;int32&gt; peerASN, string primaryPeerAddressPrefix, string secondaryPeerAddressPrefix, string primaryAzurePort, string secondaryAzurePort, string sharedKey, valuetype System.Nullable`1&lt;int32&gt; vlanId, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats stats, string provisioningState, string gatewayManagerEtag, string lastModifiedBy, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilter, class Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig ipv6PeeringConfig, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter,Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering : string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * string * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats * string * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter * Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering (id, peeringType, state, azureASN, peerASN, primaryPeerAddressPrefix, secondaryPeerAddressPrefix, primaryAzurePort, secondaryAzurePort, sharedKey, vlanId, microsoftPeeringConfig, stats, provisioningState, gatewayManagerEtag, lastModifiedBy, routeFilter, ipv6PeeringConfig, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="peeringType" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="azureASN" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="peerASN" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="primaryPeerAddressPrefix" Type="System.String" />
        <Parameter Name="secondaryPeerAddressPrefix" Type="System.String" />
        <Parameter Name="primaryAzurePort" Type="System.String" />
        <Parameter Name="secondaryAzurePort" Type="System.String" />
        <Parameter Name="sharedKey" Type="System.String" />
        <Parameter Name="vlanId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="microsoftPeeringConfig" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig" />
        <Parameter Name="stats" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="gatewayManagerEtag" Type="System.String" />
        <Parameter Name="lastModifiedBy" Type="System.String" />
        <Parameter Name="routeFilter" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
        <Parameter Name="ipv6PeeringConfig" Type="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="02aae-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="02aae-103">Resource ID.</span></span></param>
        <param name="peeringType"><span data-ttu-id="02aae-104">PeeringType です。</span><span class="sxs-lookup"><span data-stu-id="02aae-104">The PeeringType.</span></span> <span data-ttu-id="02aae-105">使用可能な値が: 'AzurePublicPeering'、'AzurePrivatePeering' および 'MicrosoftPeering' です。</span><span class="sxs-lookup"><span data-stu-id="02aae-105">Possible values are: 'AzurePublicPeering', 'AzurePrivatePeering', and 'MicrosoftPeering'.</span></span> <span data-ttu-id="02aae-106">使用可能な値が含まれます: 'AzurePublicPeering'、'AzurePrivatePeering'、'MicrosoftPeering'</span><span class="sxs-lookup"><span data-stu-id="02aae-106">Possible values include: 'AzurePublicPeering', 'AzurePrivatePeering', 'MicrosoftPeering'</span></span></param>
        <param name="state"><span data-ttu-id="02aae-107">ピアリングの状態。</span><span class="sxs-lookup"><span data-stu-id="02aae-107">The state of peering.</span></span> <span data-ttu-id="02aae-108">使用可能な値が: 'Disabled'、'Enabled' です。</span><span class="sxs-lookup"><span data-stu-id="02aae-108">Possible values are: 'Disabled' and 'Enabled'.</span></span> <span data-ttu-id="02aae-109">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="02aae-109">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <param name="azureASN"><span data-ttu-id="02aae-110">Azure の ASN です。</span><span class="sxs-lookup"><span data-stu-id="02aae-110">The Azure ASN.</span></span></param>
        <param name="peerASN"><span data-ttu-id="02aae-111">ピア ASN です。</span><span class="sxs-lookup"><span data-stu-id="02aae-111">The peer ASN.</span></span></param>
        <param name="primaryPeerAddressPrefix"><span data-ttu-id="02aae-112">プライマリ アドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="02aae-112">The primary address prefix.</span></span></param>
        <param name="secondaryPeerAddressPrefix"><span data-ttu-id="02aae-113">セカンダリ アドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="02aae-113">The secondary address prefix.</span></span></param>
        <param name="primaryAzurePort"><span data-ttu-id="02aae-114">プライマリ ポートです。</span><span class="sxs-lookup"><span data-stu-id="02aae-114">The primary port.</span></span></param>
        <param name="secondaryAzurePort"><span data-ttu-id="02aae-115">セカンダリ ポートです。</span><span class="sxs-lookup"><span data-stu-id="02aae-115">The secondary port.</span></span></param>
        <param name="sharedKey"><span data-ttu-id="02aae-116">共有キー。</span><span class="sxs-lookup"><span data-stu-id="02aae-116">The shared key.</span></span></param>
        <param name="vlanId"><span data-ttu-id="02aae-117">VLAN id。</span><span class="sxs-lookup"><span data-stu-id="02aae-117">The VLAN ID.</span></span></param>
        <param name="microsoftPeeringConfig"><span data-ttu-id="02aae-118">Microsoft ピアリング構成します。</span><span class="sxs-lookup"><span data-stu-id="02aae-118">The Microsoft peering configuration.</span></span></param>
        <param name="stats"><span data-ttu-id="02aae-119">統計のピアリングを取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-119">Gets peering stats.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="02aae-120">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-120">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="02aae-121">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="02aae-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="gatewayManagerEtag"><span data-ttu-id="02aae-122">GatewayManager Etag です。</span><span class="sxs-lookup"><span data-stu-id="02aae-122">The GatewayManager Etag.</span></span></param>
        <param name="lastModifiedBy"><span data-ttu-id="02aae-123">プロバイダーまたは顧客の最後に変更された、ピアリングするかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-123">Gets whether the provider or the customer last modified the peering.</span></span></param>
        <param name="routeFilter"><span data-ttu-id="02aae-124">RouteFilter リソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="02aae-124">The reference of the RouteFilter resource.</span></span></param>
        <param name="ipv6PeeringConfig"><span data-ttu-id="02aae-125">IPv6 ピアリング構成します。</span><span class="sxs-lookup"><span data-stu-id="02aae-125">The IPv6 peering configuration.</span></span></param>
        <param name="name"><span data-ttu-id="02aae-126">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-126">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="02aae-127">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="02aae-127">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="02aae-128">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="02aae-128">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="02aae-129">ExpressRouteCircuitPeering クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02aae-129">Initializes a new instance of the ExpressRouteCircuitPeering class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureASN">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AzureASN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AzureASN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.AzureASN" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureASN As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AzureASN : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.AzureASN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azureASN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-130">取得または Azure ASN を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-130">Gets or sets the Azure ASN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="02aae-131">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-131">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayManagerEtag">
      <MemberSignature Language="C#" Value="public string GatewayManagerEtag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayManagerEtag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.GatewayManagerEtag" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayManagerEtag As String" />
      <MemberSignature Language="F#" Value="member this.GatewayManagerEtag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.GatewayManagerEtag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayManagerEtag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-132">取得または GatewayManager Etag を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-132">Gets or sets the GatewayManager Etag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv6PeeringConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig Ipv6PeeringConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig Ipv6PeeringConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Ipv6PeeringConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv6PeeringConfig As Ipv6ExpressRouteCircuitPeeringConfig" />
      <MemberSignature Language="F#" Value="member this.Ipv6PeeringConfig : Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Ipv6PeeringConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipv6PeeringConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-133">取得または IPv6 ピアリング構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-133">Gets or sets the IPv6 peering configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedBy">
      <MemberSignature Language="C#" Value="public string LastModifiedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastModifiedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.LastModifiedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModifiedBy As String" />
      <MemberSignature Language="F#" Value="member this.LastModifiedBy : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.LastModifiedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-134">プロバイダーまたは顧客の最後に変更された、ピアリングするかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-134">Gets whether the provider or the customer last modified the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftPeeringConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.MicrosoftPeeringConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftPeeringConfig As ExpressRouteCircuitPeeringConfig" />
      <MemberSignature Language="F#" Value="member this.MicrosoftPeeringConfig : Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.MicrosoftPeeringConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftPeeringConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-135">取得または Microsoft ピアリング構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-135">Gets or sets the Microsoft peering configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="02aae-136">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-136">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="02aae-137">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="02aae-137">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeerASN">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PeerASN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PeerASN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeerASN" />
      <MemberSignature Language="VB.NET" Value="Public Property PeerASN As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PeerASN : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeerASN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peerASN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-138">取得またはピア ASN を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-138">Gets or sets the peer ASN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeeringType">
      <MemberSignature Language="C#" Value="public string PeeringType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PeeringType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeeringType" />
      <MemberSignature Language="VB.NET" Value="Public Property PeeringType As String" />
      <MemberSignature Language="F#" Value="member this.PeeringType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeeringType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peeringType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-139">取得または、PeeringType を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-139">Gets or sets the PeeringType.</span></span> <span data-ttu-id="02aae-140">使用可能な値が: 'AzurePublicPeering'、'AzurePrivatePeering' および 'MicrosoftPeering' です。</span><span class="sxs-lookup"><span data-stu-id="02aae-140">Possible values are: 'AzurePublicPeering', 'AzurePrivatePeering', and 'MicrosoftPeering'.</span></span> <span data-ttu-id="02aae-141">使用可能な値が含まれます: 'AzurePublicPeering'、'AzurePrivatePeering'、'MicrosoftPeering'</span><span class="sxs-lookup"><span data-stu-id="02aae-141">Possible values include: 'AzurePublicPeering', 'AzurePrivatePeering', 'MicrosoftPeering'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAzurePort">
      <MemberSignature Language="C#" Value="public string PrimaryAzurePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAzurePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryAzurePort" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAzurePort As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAzurePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryAzurePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryAzurePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-142">取得またはポートのプライマリを設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-142">Gets or sets the primary port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string PrimaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryPeerAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-143">取得またはプライマリ アドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-143">Gets or sets the primary address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.ProvisioningState" />
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
            <span data-ttu-id="02aae-144">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-144">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="02aae-145">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="02aae-145">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.RouteFilter RouteFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.RouteFilter RouteFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.RouteFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteFilter As RouteFilter" />
      <MemberSignature Language="F#" Value="member this.RouteFilter : Microsoft.Azure.Management.Network.Models.RouteFilter with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.RouteFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-146">取得または RouteFilter リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-146">Gets or sets the reference of the RouteFilter resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryAzurePort">
      <MemberSignature Language="C#" Value="public string SecondaryAzurePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryAzurePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryAzurePort" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryAzurePort As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryAzurePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryAzurePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryAzurePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-147">取得またはセカンダリ ポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-147">Gets or sets the secondary port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string SecondaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryPeerAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-148">取得またはセカンダリのアドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-148">Gets or sets the secondary address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedKey">
      <MemberSignature Language="C#" Value="public string SharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-149">取得または共有キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-149">Gets or sets the shared key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-150">取得またはピアリングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="02aae-150">Gets or sets the state of peering.</span></span> <span data-ttu-id="02aae-151">使用可能な値が: 'Disabled'、'Enabled' です。</span><span class="sxs-lookup"><span data-stu-id="02aae-151">Possible values are: 'Disabled' and 'Enabled'.</span></span> <span data-ttu-id="02aae-152">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="02aae-152">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As ExpressRouteCircuitStats" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Stats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.stats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-153">統計のピアリングを取得します。</span><span class="sxs-lookup"><span data-stu-id="02aae-153">Gets peering stats.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VlanId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VlanId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VlanId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.VlanId" />
      <MemberSignature Language="VB.NET" Value="Public Property VlanId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VlanId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.VlanId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vlanId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02aae-154">取得または VLAN ID を設定します</span><span class="sxs-lookup"><span data-stu-id="02aae-154">Gets or sets the VLAN ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>