<Type Name="InboundNatRule" FullName="Microsoft.Azure.Management.Network.Models.InboundNatRule">
  <TypeSignature Language="C#" Value="public class InboundNatRule : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatRule extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.InboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatRule&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type InboundNatRule = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="e05bf-101">ロード バランサーの着信 NAT ルール。</span><span class="sxs-lookup"><span data-stu-id="e05bf-101">Inbound NAT rule of the load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.InboundNatRule.#ctor" />
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
            <span data-ttu-id="e05bf-102">InboundNatRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-102">Initializes a new instance of the InboundNatRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRule (string id = null, Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration = null, Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration backendIPConfiguration = null, string protocol = null, Nullable&lt;int&gt; frontendPort = null, Nullable&lt;int&gt; backendPort = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, Nullable&lt;bool&gt; enableFloatingIP = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.Network.Models.SubResource frontendIPConfiguration, class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration backendIPConfiguration, string protocol, valuetype System.Nullable`1&lt;int32&gt; frontendPort, valuetype System.Nullable`1&lt;int32&gt; backendPort, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, valuetype System.Nullable`1&lt;bool&gt; enableFloatingIP, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.InboundNatRule.#ctor(System.String,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional backendIPConfiguration As NetworkInterfaceIPConfiguration = null, Optional protocol As String = null, Optional frontendPort As Nullable(Of Integer) = null, Optional backendPort As Nullable(Of Integer) = null, Optional idleTimeoutInMinutes As Nullable(Of Integer) = null, Optional enableFloatingIP As Nullable(Of Boolean) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.InboundNatRule : string * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.InboundNatRule" Usage="new Microsoft.Azure.Management.Network.Models.InboundNatRule (id, frontendIPConfiguration, backendIPConfiguration, protocol, frontendPort, backendPort, idleTimeoutInMinutes, enableFloatingIP, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="backendIPConfiguration" Type="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="frontendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="backendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableFloatingIP" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e05bf-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="e05bf-103">Resource ID.</span></span></param>
        <param name="frontendIPConfiguration"><span data-ttu-id="e05bf-104">フロント エンド IP アドレスへの参照。</span><span class="sxs-lookup"><span data-stu-id="e05bf-104">A reference to frontend IP addresses.</span></span></param>
        <param name="backendIPConfiguration"><span data-ttu-id="e05bf-105">VM のネットワーク インターフェイスで定義されているプライベート IP アドレスへの参照。</span><span class="sxs-lookup"><span data-stu-id="e05bf-105">A reference to a private IP address defined on a network interface of a VM.</span></span> <span data-ttu-id="e05bf-106">各フロント エンド IP 構成のフロント エンド ポートに送信されるトラフィックは、バックエンド ip アドレスに転送されます。</span><span class="sxs-lookup"><span data-stu-id="e05bf-106">Traffic sent to the frontend port of each of the frontend IP configurations is forwarded to the backend IP.</span></span></param>
        <param name="protocol"><span data-ttu-id="e05bf-107">使用可能な値が含まれます: 'Udp'、'Tcp'、'All'</span><span class="sxs-lookup"><span data-stu-id="e05bf-107">Possible values include: 'Udp', 'Tcp', 'All'</span></span></param>
        <param name="frontendPort"><span data-ttu-id="e05bf-108">外部エンドポイントのポートです。</span><span class="sxs-lookup"><span data-stu-id="e05bf-108">The port for the external endpoint.</span></span> <span data-ttu-id="e05bf-109">各規則のポート番号は、ロード バランサー内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="e05bf-109">Port numbers for each rule must be unique within the Load Balancer.</span></span>
            <span data-ttu-id="e05bf-110">許容される値の範囲は 1 ~ 65534 です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-110">Acceptable values range from 1 to 65534.</span></span></param>
        <param name="backendPort"><span data-ttu-id="e05bf-111">内部エンドポイントで使用されるポートです。</span><span class="sxs-lookup"><span data-stu-id="e05bf-111">The port used for the internal endpoint.</span></span>
            <span data-ttu-id="e05bf-112">許容される値の範囲は 1 ~ 65535 です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-112">Acceptable values range from 1 to 65535.</span></span></param>
        <param name="idleTimeoutInMinutes"><span data-ttu-id="e05bf-113">TCP アイドル接続のタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="e05bf-113">The timeout for the TCP idle connection.</span></span> <span data-ttu-id="e05bf-114">値は、4 ~ 30 分間に設定できます。</span><span class="sxs-lookup"><span data-stu-id="e05bf-114">The value can be set between 4 and 30 minutes.</span></span> <span data-ttu-id="e05bf-115">既定値は、4 分です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-115">The default value is 4 minutes.</span></span> <span data-ttu-id="e05bf-116">この要素は、プロトコルが TCP に設定されている場合にのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-116">This element is only used when the protocol is set to TCP.</span></span></param>
        <param name="enableFloatingIP"><span data-ttu-id="e05bf-117">SQL AlwaysOn 可用性グループの構成に必要な floating IP 機能用に仮想マシンのエンドポイントを構成します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-117">Configures a virtual machine's endpoint for the floating IP capability required to configure a SQL AlwaysOn Availability Group.</span></span> <span data-ttu-id="e05bf-118">SQL server で SQL AlwaysOn 可用性グループを使用する場合、この設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-118">This setting is required when using the SQL AlwaysOn Availability Groups in SQL server.</span></span> <span data-ttu-id="e05bf-119">エンドポイントを作成した後、この設定を変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="e05bf-119">This setting can't be changed after you create the endpoint.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="e05bf-120">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-120">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="e05bf-121">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="e05bf-122">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-122">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="e05bf-123">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="e05bf-123">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="e05bf-124">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-124">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="e05bf-125">InboundNatRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-125">Initializes a new instance of the InboundNatRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration BackendIPConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration BackendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfiguration As NetworkInterfaceIPConfiguration" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfiguration : Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05bf-126">VM のネットワーク インターフェイスで定義されているプライベート IP アドレスへの参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-126">Gets a reference to a private IP address defined on a network interface of a VM.</span></span> <span data-ttu-id="e05bf-127">各フロント エンド IP 構成のフロント エンド ポートに送信されるトラフィックは、バックエンド ip アドレスに転送されます。</span><span class="sxs-lookup"><span data-stu-id="e05bf-127">Traffic sent to the frontend port of each of the frontend IP configurations is forwarded to the backend IP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05bf-128">取得または内部エンドポイントで使用されるポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-128">Gets or sets the port used for the internal endpoint.</span></span> <span data-ttu-id="e05bf-129">許容される値の範囲は 1 ~ 65535 です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-129">Acceptable values range from 1 to 65535.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFloatingIP">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableFloatingIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableFloatingIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.EnableFloatingIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFloatingIP As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableFloatingIP : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.EnableFloatingIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableFloatingIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05bf-130">取得または設定は、SQL AlwaysOn 可用性グループの構成に必要な floating IP 機能用に仮想マシンのエンドポイントを構成します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-130">Gets or sets configures a virtual machine's endpoint for the floating IP capability required to configure a SQL AlwaysOn Availability Group.</span></span> <span data-ttu-id="e05bf-131">SQL server で SQL AlwaysOn 可用性グループを使用する場合、この設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-131">This setting is required when using the SQL AlwaysOn Availability Groups in SQL server.</span></span> <span data-ttu-id="e05bf-132">エンドポイントを作成した後、この設定を変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="e05bf-132">This setting can't be changed after you create the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.Etag" />
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
            <span data-ttu-id="e05bf-133">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="e05bf-133">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource FrontendIPConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource FrontendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05bf-134">取得またはフロント エンド IP アドレスへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-134">Gets or sets a reference to frontend IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.FrontendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05bf-135">取得または外部エンドポイントのポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-135">Gets or sets the port for the external endpoint.</span></span> <span data-ttu-id="e05bf-136">各規則のポート番号は、ロード バランサー内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="e05bf-136">Port numbers for each rule must be unique within the Load Balancer.</span></span> <span data-ttu-id="e05bf-137">許容される値の範囲は 1 ~ 65534 です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-137">Acceptable values range from 1 to 65534.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idleTimeoutInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05bf-138">取得または TCP アイドル接続のタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-138">Gets or sets the timeout for the TCP idle connection.</span></span> <span data-ttu-id="e05bf-139">値は、4 ~ 30 分間に設定できます。</span><span class="sxs-lookup"><span data-stu-id="e05bf-139">The value can be set between 4 and 30 minutes.</span></span> <span data-ttu-id="e05bf-140">既定値は、4 分です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-140">The default value is 4 minutes.</span></span>
            <span data-ttu-id="e05bf-141">この要素は、プロトコルが TCP に設定されている場合にのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-141">This element is only used when the protocol is set to TCP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.Name" />
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
            <span data-ttu-id="e05bf-142">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-142">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="e05bf-143">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="e05bf-143">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e05bf-144">取得または設定可能な値が含まれます: 'Udp'、'Tcp'、'All'</span><span class="sxs-lookup"><span data-stu-id="e05bf-144">Gets or sets possible values include: 'Udp', 'Tcp', 'All'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.InboundNatRule.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.InboundNatRule.ProvisioningState" />
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
            <span data-ttu-id="e05bf-145">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e05bf-145">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="e05bf-146">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="e05bf-146">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>