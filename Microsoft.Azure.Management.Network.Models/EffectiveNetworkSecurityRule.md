<Type Name="EffectiveNetworkSecurityRule" FullName="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule">
  <TypeSignature Language="C#" Value="public class EffectiveNetworkSecurityRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveNetworkSecurityRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveNetworkSecurityRule" />
  <TypeSignature Language="F#" Value="type EffectiveNetworkSecurityRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e1b8b-101">有効なネットワーク セキュリティ ルール。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-101">Effective network security rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.#ctor" />
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
            <span data-ttu-id="e1b8b-102">EffectiveNetworkSecurityRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-102">Initializes a new instance of the EffectiveNetworkSecurityRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityRule (string name = null, string protocol = null, string sourcePortRange = null, string destinationPortRange = null, System.Collections.Generic.IList&lt;string&gt; sourcePortRanges = null, System.Collections.Generic.IList&lt;string&gt; destinationPortRanges = null, string sourceAddressPrefix = null, string destinationAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; sourceAddressPrefixes = null, System.Collections.Generic.IList&lt;string&gt; destinationAddressPrefixes = null, System.Collections.Generic.IList&lt;string&gt; expandedSourceAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; expandedDestinationAddressPrefix = null, string access = null, Nullable&lt;int&gt; priority = null, string direction = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string protocol, string sourcePortRange, string destinationPortRange, class System.Collections.Generic.IList`1&lt;string&gt; sourcePortRanges, class System.Collections.Generic.IList`1&lt;string&gt; destinationPortRanges, string sourceAddressPrefix, string destinationAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; sourceAddressPrefixes, class System.Collections.Generic.IList`1&lt;string&gt; destinationAddressPrefixes, class System.Collections.Generic.IList`1&lt;string&gt; expandedSourceAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; expandedDestinationAddressPrefix, string access, valuetype System.Nullable`1&lt;int32&gt; priority, string direction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional protocol As String = null, Optional sourcePortRange As String = null, Optional destinationPortRange As String = null, Optional sourcePortRanges As IList(Of String) = null, Optional destinationPortRanges As IList(Of String) = null, Optional sourceAddressPrefix As String = null, Optional destinationAddressPrefix As String = null, Optional sourceAddressPrefixes As IList(Of String) = null, Optional destinationAddressPrefixes As IList(Of String) = null, Optional expandedSourceAddressPrefix As IList(Of String) = null, Optional expandedDestinationAddressPrefix As IList(Of String) = null, Optional access As String = null, Optional priority As Nullable(Of Integer) = null, Optional direction As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule" Usage="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule (name, protocol, sourcePortRange, destinationPortRange, sourcePortRanges, destinationPortRanges, sourceAddressPrefix, destinationAddressPrefix, sourceAddressPrefixes, destinationAddressPrefixes, expandedSourceAddressPrefix, expandedDestinationAddressPrefix, access, priority, direction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="sourcePortRange" Type="System.String" />
        <Parameter Name="destinationPortRange" Type="System.String" />
        <Parameter Name="sourcePortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationPortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="sourceAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="expandedSourceAddressPrefix" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="expandedDestinationAddressPrefix" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="direction" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e1b8b-103">(ユーザーによって作成される) 場合に、ユーザーが指定したセキュリティの規則の名前。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-103">The name of the security rule specified by the user (if created by the user).</span></span></param>
        <param name="protocol"><span data-ttu-id="e1b8b-104">この規則を適用するネットワーク プロトコルです。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-104">The network protocol this rule applies to.</span></span>
            <span data-ttu-id="e1b8b-105">使用可能な値が: 'Tcp'、'Udp'、'All' とします。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-105">Possible values are: 'Tcp', 'Udp', and 'All'.</span></span> <span data-ttu-id="e1b8b-106">使用可能な値が含まれます: 'Tcp'、'Udp'、'All'</span><span class="sxs-lookup"><span data-stu-id="e1b8b-106">Possible values include: 'Tcp', 'Udp', 'All'</span></span></param>
        <param name="sourcePortRange"><span data-ttu-id="e1b8b-107">発信元ポートまたは範囲。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-107">The source port or range.</span></span></param>
        <param name="destinationPortRange"><span data-ttu-id="e1b8b-108">宛先ポートまたは範囲。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-108">The destination port or range.</span></span></param>
        <param name="sourcePortRanges"><span data-ttu-id="e1b8b-109">ソースのポート範囲です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-109">The source port ranges.</span></span> <span data-ttu-id="e1b8b-110">予期される値は、1 つの整数 0 ~ 65535 の範囲を使用して、'-' 区切り記号 (例: 100 ~ 400)、またはアスタリスク (\*) として</span><span class="sxs-lookup"><span data-stu-id="e1b8b-110">Expected values include a single integer between 0 and 65535, a range using '-' as seperator (e.g. 100-400), or an asterix (\*)</span></span></param>
        <param name="destinationPortRanges"><span data-ttu-id="e1b8b-111">移行先のポート範囲です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-111">The destination port ranges.</span></span>
            <span data-ttu-id="e1b8b-112">予期される値は、1 つの整数 0 ~ 65535 の範囲を使用して、'-' 区切り記号 (例: 100 ~ 400)、またはアスタリスク (\*) として</span><span class="sxs-lookup"><span data-stu-id="e1b8b-112">Expected values include a single integer between 0 and 65535, a range using '-' as seperator (e.g. 100-400), or an asterix (\*)</span></span></param>
        <param name="sourceAddressPrefix"><span data-ttu-id="e1b8b-113">発信元アドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-113">The source address prefix.</span></span></param>
        <param name="destinationAddressPrefix"><span data-ttu-id="e1b8b-114">移行先のアドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-114">The destination address prefix.</span></span></param>
        <param name="sourceAddressPrefixes"><span data-ttu-id="e1b8b-115">ソースのアドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-115">The source address prefixes.</span></span>
            <span data-ttu-id="e1b8b-116">予期される値には、CIDR IP の範囲、既定のタグ (VirtualNetwork、AureLoadBalancer、インターネット)、システムのタグ、およびアスタリスク (\*) が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-116">Expected values include CIDR IP ranges, Default Tags (VirtualNetwork, AureLoadBalancer, Internet), System Tags, and the asterix (\*).</span></span></param>
        <param name="destinationAddressPrefixes"><span data-ttu-id="e1b8b-117">移行先のアドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-117">The destination address prefixes.</span></span> <span data-ttu-id="e1b8b-118">予期される値には、CIDR IP の範囲、既定のタグ (VirtualNetwork、AureLoadBalancer、インターネット)、システムのタグ、およびアスタリスク (\*) が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-118">Expected values include CIDR IP ranges, Default Tags (VirtualNetwork, AureLoadBalancer, Internet), System Tags, and the asterix (\*).</span></span></param>
        <param name="expandedSourceAddressPrefix"><span data-ttu-id="e1b8b-119">展開したソース アドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-119">The expanded source address prefix.</span></span></param>
        <param name="expandedDestinationAddressPrefix"><span data-ttu-id="e1b8b-120">展開先のアドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-120">Expanded destination address prefix.</span></span></param>
        <param name="access"><span data-ttu-id="e1b8b-121">かどうかのネットワーク トラフィックが許可または拒否します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-121">Whether network traffic is allowed or denied.</span></span>
            <span data-ttu-id="e1b8b-122">使用可能な値が: 'Allow' および 'Deny' です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-122">Possible values are: 'Allow' and 'Deny'.</span></span> <span data-ttu-id="e1b8b-123">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-123">Possible values include: 'Allow', 'Deny'</span></span></param>
        <param name="priority"><span data-ttu-id="e1b8b-124">ルールの優先度です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-124">The priority of the rule.</span></span></param>
        <param name="direction"><span data-ttu-id="e1b8b-125">ルールの方向です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-125">The direction of the rule.</span></span> <span data-ttu-id="e1b8b-126">使用可能な値が: '受信および送信' です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-126">Possible values are: 'Inbound and Outbound'.</span></span> <span data-ttu-id="e1b8b-127">使用可能な値が含まれます: '受信'、'送信'</span><span class="sxs-lookup"><span data-stu-id="e1b8b-127">Possible values include: 'Inbound', 'Outbound'</span></span></param>
        <summary>
            <span data-ttu-id="e1b8b-128">EffectiveNetworkSecurityRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-128">Initializes a new instance of the EffectiveNetworkSecurityRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-129">取得またはネットワーク トラフィックを許可または拒否するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-129">Gets or sets whether network traffic is allowed or denied.</span></span> <span data-ttu-id="e1b8b-130">使用可能な値が: 'Allow' および 'Deny' です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-130">Possible values are: 'Allow' and 'Deny'.</span></span> <span data-ttu-id="e1b8b-131">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-131">Possible values include: 'Allow', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public string DestinationAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-132">取得または宛先アドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-132">Gets or sets the destination address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-133">取得またはアドレス プレフィックスの送信先を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-133">Gets or sets the destination address prefixes.</span></span> <span data-ttu-id="e1b8b-134">予期される値には、CIDR IP の範囲、既定のタグ (VirtualNetwork、AureLoadBalancer、インターネット)、システムのタグ、およびアスタリスク (\*) が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-134">Expected values include CIDR IP ranges, Default Tags (VirtualNetwork, AureLoadBalancer, Internet), System Tags, and the asterix (\*).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRange">
      <MemberSignature Language="C#" Value="public string DestinationPortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationPortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRange As String" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationPortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-135">取得または宛先ポートまたは範囲を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-135">Gets or sets the destination port or range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationPortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationPortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.DestinationPortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationPortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-136">取得または送信先のポート範囲を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-136">Gets or sets the destination port ranges.</span></span> <span data-ttu-id="e1b8b-137">予期される値は、1 つの整数 0 ~ 65535 の範囲を使用して、'-' 区切り記号 (例: 100 ~ 400)、またはアスタリスク (\*) として</span><span class="sxs-lookup"><span data-stu-id="e1b8b-137">Expected values include a single integer between 0 and 65535, a range using '-' as seperator (e.g. 100-400), or an asterix (\*)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-138">取得またはルールの方向を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-138">Gets or sets the direction of the rule.</span></span> <span data-ttu-id="e1b8b-139">使用可能な値が: '受信および送信' です。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-139">Possible values are: 'Inbound and Outbound'.</span></span> <span data-ttu-id="e1b8b-140">使用可能な値が含まれます: '受信'、'送信'</span><span class="sxs-lookup"><span data-stu-id="e1b8b-140">Possible values include: 'Inbound', 'Outbound'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandedDestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ExpandedDestinationAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ExpandedDestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedDestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandedDestinationAddressPrefix As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ExpandedDestinationAddressPrefix : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedDestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expandedDestinationAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-141">取得または展開先のアドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-141">Gets or sets expanded destination address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandedSourceAddressPrefix">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ExpandedSourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ExpandedSourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedSourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandedSourceAddressPrefix As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ExpandedSourceAddressPrefix : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.ExpandedSourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expandedSourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-142">取得または展開のソース アドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-142">Gets or sets the expanded source address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Name" />
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
            <span data-ttu-id="e1b8b-143">取得または設定 (ユーザーによって作成される) 場合に、ユーザーが指定したセキュリティの規則の名前。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-143">Gets or sets the name of the security rule specified by the user (if created by the user).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-144">取得またはルールの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-144">Gets or sets the priority of the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-145">取得または、この規則の適用先のネットワーク プロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-145">Gets or sets the network protocol this rule applies to.</span></span> <span data-ttu-id="e1b8b-146">使用可能な値が: 'Tcp'、'Udp'、'All' とします。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-146">Possible values are: 'Tcp', 'Udp', and 'All'.</span></span> <span data-ttu-id="e1b8b-147">使用可能な値が含まれます: 'Tcp'、'Udp'、'All'</span><span class="sxs-lookup"><span data-stu-id="e1b8b-147">Possible values include: 'Tcp', 'Udp', 'All'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-148">取得または発信元アドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-148">Gets or sets the source address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourceAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourceAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourceAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-149">取得またはソース アドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-149">Gets or sets the source address prefixes.</span></span> <span data-ttu-id="e1b8b-150">予期される値には、CIDR IP の範囲、既定のタグ (VirtualNetwork、AureLoadBalancer、インターネット)、システムのタグ、およびアスタリスク (\*) が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-150">Expected values include CIDR IP ranges, Default Tags (VirtualNetwork, AureLoadBalancer, Internet), System Tags, and the asterix (\*).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRange">
      <MemberSignature Language="C#" Value="public string SourcePortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourcePortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRange As String" />
      <MemberSignature Language="F#" Value="member this.SourcePortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourcePortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-151">取得または送信元ポートまたは範囲を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-151">Gets or sets the source port or range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourcePortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourcePortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourcePortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityRule.SourcePortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourcePortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b8b-152">取得またはソース ポート範囲を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1b8b-152">Gets or sets the source port ranges.</span></span> <span data-ttu-id="e1b8b-153">予期される値は、1 つの整数 0 ~ 65535 の範囲を使用して、'-' 区切り記号 (例: 100 ~ 400)、またはアスタリスク (\*) として</span><span class="sxs-lookup"><span data-stu-id="e1b8b-153">Expected values include a single integer between 0 and 65535, a range using '-' as seperator (e.g. 100-400), or an asterix (\*)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>