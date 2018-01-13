<Type Name="VirtualNetworkGatewayConnection" FullName="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection">
  <TypeSignature Language="C#" Value="public class VirtualNetworkGatewayConnection : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkGatewayConnection extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkGatewayConnection&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewayConnection = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="39980-101">一般的なリソースについての一般的なクラス</span><span class="sxs-lookup"><span data-stu-id="39980-101">A common class for general resource information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGatewayConnection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.#ctor" />
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
            <span data-ttu-id="39980-102">VirtualNetworkGatewayConnection クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="39980-102">Initializes a new instance of the VirtualNetworkGatewayConnection class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGatewayConnection (Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway virtualNetworkGateway1, string connectionType, string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string authorizationKey = null, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway virtualNetworkGateway2 = null, Microsoft.Azure.Management.Network.Models.LocalNetworkGateway localNetworkGateway2 = null, Nullable&lt;int&gt; routingWeight = null, string sharedKey = null, string connectionStatus = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt; tunnelConnectionStatus = null, Nullable&lt;long&gt; egressBytesTransferred = null, Nullable&lt;long&gt; ingressBytesTransferred = null, Microsoft.Azure.Management.Network.Models.SubResource peer = null, Nullable&lt;bool&gt; enableBgp = null, Nullable&lt;bool&gt; usePolicyBasedTrafficSelectors = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt; ipsecPolicies = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway virtualNetworkGateway1, string connectionType, string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string authorizationKey, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway virtualNetworkGateway2, class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway localNetworkGateway2, valuetype System.Nullable`1&lt;int32&gt; routingWeight, string sharedKey, string connectionStatus, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt; tunnelConnectionStatus, valuetype System.Nullable`1&lt;int64&gt; egressBytesTransferred, valuetype System.Nullable`1&lt;int64&gt; ingressBytesTransferred, class Microsoft.Azure.Management.Network.Models.SubResource peer, valuetype System.Nullable`1&lt;bool&gt; enableBgp, valuetype System.Nullable`1&lt;bool&gt; usePolicyBasedTrafficSelectors, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt; ipsecPolicies, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.#ctor(Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway,Microsoft.Azure.Management.Network.Models.LocalNetworkGateway,System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.Azure.Management.Network.Models.SubResource,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.IpsecPolicy},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (virtualNetworkGateway1 As VirtualNetworkGateway, connectionType As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional authorizationKey As String = null, Optional virtualNetworkGateway2 As VirtualNetworkGateway = null, Optional localNetworkGateway2 As LocalNetworkGateway = null, Optional routingWeight As Nullable(Of Integer) = null, Optional sharedKey As String = null, Optional connectionStatus As String = null, Optional tunnelConnectionStatus As IList(Of TunnelConnectionHealth) = null, Optional egressBytesTransferred As Nullable(Of Long) = null, Optional ingressBytesTransferred As Nullable(Of Long) = null, Optional peer As SubResource = null, Optional enableBgp As Nullable(Of Boolean) = null, Optional usePolicyBasedTrafficSelectors As Nullable(Of Boolean) = null, Optional ipsecPolicies As IList(Of IpsecPolicy) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection : Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway * string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway * Microsoft.Azure.Management.Network.Models.LocalNetworkGateway * Nullable&lt;int&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.Network.Models.SubResource * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" Usage="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection (virtualNetworkGateway1, connectionType, id, name, type, location, tags, authorizationKey, virtualNetworkGateway2, localNetworkGateway2, routingWeight, sharedKey, connectionStatus, tunnelConnectionStatus, egressBytesTransferred, ingressBytesTransferred, peer, enableBgp, usePolicyBasedTrafficSelectors, ipsecPolicies, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualNetworkGateway1" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
        <Parameter Name="connectionType" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="authorizationKey" Type="System.String" />
        <Parameter Name="virtualNetworkGateway2" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
        <Parameter Name="localNetworkGateway2" Type="Microsoft.Azure.Management.Network.Models.LocalNetworkGateway" />
        <Parameter Name="routingWeight" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sharedKey" Type="System.String" />
        <Parameter Name="connectionStatus" Type="System.String" />
        <Parameter Name="tunnelConnectionStatus" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt;" />
        <Parameter Name="egressBytesTransferred" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="ingressBytesTransferred" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="peer" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="enableBgp" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="usePolicyBasedTrafficSelectors" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ipsecPolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualNetworkGateway1"><span data-ttu-id="39980-103">仮想ネットワーク ゲートウェイ リソースへの参照。</span><span class="sxs-lookup"><span data-stu-id="39980-103">The reference to virtual network gateway resource.</span></span></param>
        <param name="connectionType"><span data-ttu-id="39980-104">ゲートウェイ接続の種類です。</span><span class="sxs-lookup"><span data-stu-id="39980-104">Gateway connection type.</span></span> <span data-ttu-id="39980-105">使用可能な値が: 'Ipsec'、'Vnet2Vnet'、'ExpressRoute' および ' がない場合。</span><span class="sxs-lookup"><span data-stu-id="39980-105">Possible values are: 'Ipsec','Vnet2Vnet','ExpressRoute', and 'VPNClient.</span></span>
            <span data-ttu-id="39980-106">使用可能な値が含まれます 'IPsec'、'Vnet2Vnet'、'ExpressRoute'、'がない場合'。</span><span class="sxs-lookup"><span data-stu-id="39980-106">Possible values include: 'IPsec', 'Vnet2Vnet', 'ExpressRoute', 'VPNClient'</span></span></param>
        <param name="id"><span data-ttu-id="39980-107">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="39980-107">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="39980-108">リソース名。</span><span class="sxs-lookup"><span data-stu-id="39980-108">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="39980-109">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="39980-109">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="39980-110">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="39980-110">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="39980-111">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="39980-111">Resource tags.</span></span></param>
        <param name="authorizationKey"><span data-ttu-id="39980-112">AuthorizationKey です。</span><span class="sxs-lookup"><span data-stu-id="39980-112">The authorizationKey.</span></span></param>
        <param name="virtualNetworkGateway2"><span data-ttu-id="39980-113">仮想ネットワーク ゲートウェイ リソースへの参照。</span><span class="sxs-lookup"><span data-stu-id="39980-113">The reference to virtual network gateway resource.</span></span></param>
        <param name="localNetworkGateway2"><span data-ttu-id="39980-114">ローカル ネットワーク ゲートウェイ リソースへの参照。</span><span class="sxs-lookup"><span data-stu-id="39980-114">The reference to local network gateway resource.</span></span></param>
        <param name="routingWeight"><span data-ttu-id="39980-115">ルーティングの太さ。</span><span class="sxs-lookup"><span data-stu-id="39980-115">The routing weight.</span></span></param>
        <param name="sharedKey"><span data-ttu-id="39980-116">IPSec の共有キー。</span><span class="sxs-lookup"><span data-stu-id="39980-116">The IPSec shared key.</span></span></param>
        <param name="connectionStatus"><span data-ttu-id="39980-117">仮想ネットワーク ゲートウェイ接続の状態。</span><span class="sxs-lookup"><span data-stu-id="39980-117">Virtual network Gateway connection status.</span></span> <span data-ttu-id="39980-118">使用可能な値は 'Unknown'、'接続'、'接続' および 'NotConnected' です。</span><span class="sxs-lookup"><span data-stu-id="39980-118">Possible values are 'Unknown', 'Connecting', 'Connected' and 'NotConnected'.</span></span> <span data-ttu-id="39980-119">使用可能な値が含まれます: 'Unknown'、'接続'、'接続'、'NotConnected'</span><span class="sxs-lookup"><span data-stu-id="39980-119">Possible values include: 'Unknown', 'Connecting', 'Connected', 'NotConnected'</span></span></param>
        <param name="tunnelConnectionStatus"><span data-ttu-id="39980-120">すべてのトンネルの接続のヘルス状態のコレクションです。</span><span class="sxs-lookup"><span data-stu-id="39980-120">Collection of all tunnels' connection health status.</span></span></param>
        <param name="egressBytesTransferred"><span data-ttu-id="39980-121">送信バイト数は、この接続で転送されます。</span><span class="sxs-lookup"><span data-stu-id="39980-121">The egress bytes transferred in this connection.</span></span></param>
        <param name="ingressBytesTransferred"><span data-ttu-id="39980-122">受信バイト数は、この接続で転送されます。</span><span class="sxs-lookup"><span data-stu-id="39980-122">The ingress bytes transferred in this connection.</span></span></param>
        <param name="peer"><span data-ttu-id="39980-123">ピアリング リソースへの参照。</span><span class="sxs-lookup"><span data-stu-id="39980-123">The reference to peerings resource.</span></span></param>
        <param name="enableBgp"><span data-ttu-id="39980-124">EnableBgp フラグ</span><span class="sxs-lookup"><span data-stu-id="39980-124">EnableBgp flag</span></span></param>
        <param name="usePolicyBasedTrafficSelectors"><span data-ttu-id="39980-125">ポリシー ベースのトラフィックのセレクターを有効にします。</span><span class="sxs-lookup"><span data-stu-id="39980-125">Enable policy-based traffic selectors.</span></span></param>
        <param name="ipsecPolicies"><span data-ttu-id="39980-126">この接続で考慮する IPSec ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="39980-126">The IPSec Policies to be considered by this connection.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="39980-127">リソースの VirtualNetworkGatewayConnection リソース GUID プロパティです。</span><span class="sxs-lookup"><span data-stu-id="39980-127">The resource GUID property of the VirtualNetworkGatewayConnection resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="39980-128">VirtualNetworkGatewayConnection リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="39980-128">The provisioning state of the VirtualNetworkGatewayConnection resource.</span></span> <span data-ttu-id="39980-129">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="39980-129">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="39980-130">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="39980-130">Gets a unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="39980-131">VirtualNetworkGatewayConnection クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="39980-131">Initializes a new instance of the VirtualNetworkGatewayConnection class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationKey">
      <MemberSignature Language="C#" Value="public string AuthorizationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.AuthorizationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationKey As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.AuthorizationKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizationKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-132">取得または、authorizationKey を設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-132">Gets or sets the authorizationKey.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStatus">
      <MemberSignature Language="C#" Value="public string ConnectionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ConnectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionStatus : string" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ConnectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-133">仮想ネットワーク ゲートウェイ接続の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="39980-133">Gets virtual network Gateway connection status.</span></span> <span data-ttu-id="39980-134">使用可能な値は 'Unknown'、'接続'、'接続' および 'NotConnected' です。</span><span class="sxs-lookup"><span data-stu-id="39980-134">Possible values are 'Unknown', 'Connecting', 'Connected' and 'NotConnected'.</span></span> <span data-ttu-id="39980-135">使用可能な値が含まれます: 'Unknown'、'接続'、'接続'、'NotConnected'</span><span class="sxs-lookup"><span data-stu-id="39980-135">Possible values include: 'Unknown', 'Connecting', 'Connected', 'NotConnected'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionType">
      <MemberSignature Language="C#" Value="public string ConnectionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ConnectionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionType As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ConnectionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-136">取得またはゲートウェイ接続の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-136">Gets or sets gateway connection type.</span></span> <span data-ttu-id="39980-137">使用可能な値が: 'Ipsec'、'Vnet2Vnet'、'ExpressRoute' および ' がない場合。</span><span class="sxs-lookup"><span data-stu-id="39980-137">Possible values are: 'Ipsec','Vnet2Vnet','ExpressRoute', and 'VPNClient.</span></span> <span data-ttu-id="39980-138">使用可能な値が含まれます 'IPsec'、'Vnet2Vnet'、'ExpressRoute'、'がない場合'。</span><span class="sxs-lookup"><span data-stu-id="39980-138">Possible values include: 'IPsec', 'Vnet2Vnet', 'ExpressRoute', 'VPNClient'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EgressBytesTransferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; EgressBytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; EgressBytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.EgressBytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EgressBytesTransferred As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.EgressBytesTransferred : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.EgressBytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.egressBytesTransferred")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-139">この接続で転送された送信バイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="39980-139">Gets the egress bytes transferred in this connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBgp">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBgp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBgp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.EnableBgp" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBgp As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBgp : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.EnableBgp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableBgp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-140">取得または enableBgp フラグを設定</span><span class="sxs-lookup"><span data-stu-id="39980-140">Gets or sets enableBgp flag</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.Etag" />
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
            <span data-ttu-id="39980-141">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="39980-141">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IngressBytesTransferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IngressBytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IngressBytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.IngressBytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IngressBytesTransferred As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IngressBytesTransferred : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.IngressBytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ingressBytesTransferred")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-142">この接続で転送された受信バイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="39980-142">Gets the ingress bytes transferred in this connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsecPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt; IpsecPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt; IpsecPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.IpsecPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsecPolicies As IList(Of IpsecPolicy)" />
      <MemberSignature Language="F#" Value="member this.IpsecPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.IpsecPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipsecPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IpsecPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-143">取得またはこの接続で考慮する IPSec ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-143">Gets or sets the IPSec Policies to be considered by this connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalNetworkGateway2">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.LocalNetworkGateway LocalNetworkGateway2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.LocalNetworkGateway LocalNetworkGateway2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.LocalNetworkGateway2" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalNetworkGateway2 As LocalNetworkGateway" />
      <MemberSignature Language="F#" Value="member this.LocalNetworkGateway2 : Microsoft.Azure.Management.Network.Models.LocalNetworkGateway with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.LocalNetworkGateway2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localNetworkGateway2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LocalNetworkGateway</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-144">取得またはローカル ネットワーク ゲートウェイ リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-144">Gets or sets the reference to local network gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource Peer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource Peer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.Peer" />
      <MemberSignature Language="VB.NET" Value="Public Property Peer As SubResource" />
      <MemberSignature Language="F#" Value="member this.Peer : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.Peer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-145">取得またはピアリング リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-145">Gets or sets the reference to peerings resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ProvisioningState" />
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
            <span data-ttu-id="39980-146">VirtualNetworkGatewayConnection リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="39980-146">Gets the provisioning state of the VirtualNetworkGatewayConnection resource.</span></span> <span data-ttu-id="39980-147">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="39980-147">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="39980-148">取得またはリソース VirtualNetworkGatewayConnection リソースの GUID プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-148">Gets or sets the resource GUID property of the VirtualNetworkGatewayConnection resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoutingWeight">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RoutingWeight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RoutingWeight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.RoutingWeight" />
      <MemberSignature Language="VB.NET" Value="Public Property RoutingWeight As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RoutingWeight : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.RoutingWeight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routingWeight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-149">取得またはルーティングの重みを設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-149">Gets or sets the routing weight.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedKey">
      <MemberSignature Language="C#" Value="public string SharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.SharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.SharedKey" />
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
            <span data-ttu-id="39980-150">取得または IPSec の共有キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-150">Gets or sets the IPSec shared key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TunnelConnectionStatus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt; TunnelConnectionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt; TunnelConnectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.TunnelConnectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TunnelConnectionStatus As IList(Of TunnelConnectionHealth)" />
      <MemberSignature Language="F#" Value="member this.TunnelConnectionStatus : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt;" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.TunnelConnectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tunnelConnectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TunnelConnectionHealth&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-151">すべてのトンネルの接続のヘルス状態のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="39980-151">Gets collection of all tunnels' connection health status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePolicyBasedTrafficSelectors">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsePolicyBasedTrafficSelectors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsePolicyBasedTrafficSelectors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.UsePolicyBasedTrafficSelectors" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePolicyBasedTrafficSelectors As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsePolicyBasedTrafficSelectors : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.UsePolicyBasedTrafficSelectors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usePolicyBasedTrafficSelectors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-152">取得または設定には、ポリシー ベースのトラフィックのセレクターが有効にします。</span><span class="sxs-lookup"><span data-stu-id="39980-152">Gets or sets enable policy-based traffic selectors.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualNetworkGatewayConnection.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="39980-153">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="39980-153">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="39980-154">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="39980-154">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateway1">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway VirtualNetworkGateway1 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway VirtualNetworkGateway1" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.VirtualNetworkGateway1" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkGateway1 As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateway1 : Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.VirtualNetworkGateway1" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkGateway1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-155">取得または仮想ネットワーク ゲートウェイ リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-155">Gets or sets the reference to virtual network gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateway2">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway VirtualNetworkGateway2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway VirtualNetworkGateway2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.VirtualNetworkGateway2" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkGateway2 As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateway2 : Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection.VirtualNetworkGateway2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkGateway2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="39980-156">取得または仮想ネットワーク ゲートウェイ リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="39980-156">Gets or sets the reference to virtual network gateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>