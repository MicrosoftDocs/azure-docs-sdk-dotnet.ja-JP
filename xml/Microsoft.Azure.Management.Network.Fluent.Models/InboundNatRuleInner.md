<Type Name="InboundNatRuleInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner">
  <TypeSignature Language="C#" Value="public class InboundNatRuleInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatRuleInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatRuleInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type InboundNatRuleInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="79a68-101">ロード バランサーの着信 NAT ルール。</span><span class="sxs-lookup"><span data-stu-id="79a68-101">Inbound NAT rule of the load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRuleInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="79a68-102">InboundNatRuleInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="79a68-102">Initializes a new instance of the InboundNatRuleInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNatRuleInner (string id = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration = null, Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner backendIPConfiguration = null, string protocol = null, Nullable&lt;int&gt; frontendPort = null, Nullable&lt;int&gt; backendPort = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, Nullable&lt;bool&gt; enableFloatingIP = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner backendIPConfiguration, string protocol, valuetype System.Nullable`1&lt;int32&gt; frontendPort, valuetype System.Nullable`1&lt;int32&gt; backendPort, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, valuetype System.Nullable`1&lt;bool&gt; enableFloatingIP, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.#ctor(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional backendIPConfiguration As NetworkInterfaceIPConfigurationInner = null, Optional protocol As String = null, Optional frontendPort As Nullable(Of Integer) = null, Optional backendPort As Nullable(Of Integer) = null, Optional idleTimeoutInMinutes As Nullable(Of Integer) = null, Optional enableFloatingIP As Nullable(Of Boolean) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner : string * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner (id, frontendIPConfiguration, backendIPConfiguration, protocol, frontendPort, backendPort, idleTimeoutInMinutes, enableFloatingIP, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="backendIPConfiguration" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner" />
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
        <param name="id">To be added.</param>
        <param name="frontendIPConfiguration"><span data-ttu-id="79a68-103">フロント エンド IP アドレスへの参照。</span><span class="sxs-lookup"><span data-stu-id="79a68-103">A reference to frontend IP addresses.</span></span></param>
        <param name="backendIPConfiguration"><span data-ttu-id="79a68-104">VM のネットワーク インターフェイスで定義されているプライベート IP アドレスへの参照。</span><span class="sxs-lookup"><span data-stu-id="79a68-104">A reference to a private IP address defined on a network interface of a VM.</span></span> <span data-ttu-id="79a68-105">各フロント エンド IP 構成のフロント エンド ポートに送信されるトラフィックは、バックアップされた ip アドレスに転送されます。</span><span class="sxs-lookup"><span data-stu-id="79a68-105">Traffic sent to the frontend port of each of the frontend IP configurations is forwarded to the backed IP.</span></span></param>
        <param name="protocol"><span data-ttu-id="79a68-106">エンドポイントのトランスポート プロトコル。</span><span class="sxs-lookup"><span data-stu-id="79a68-106">The transport protocol for the endpoint.</span></span>
            <span data-ttu-id="79a68-107">使用可能な値が: 'Udp' または 'Tcp' です。</span><span class="sxs-lookup"><span data-stu-id="79a68-107">Possible values are: 'Udp' or 'Tcp'.</span></span> <span data-ttu-id="79a68-108">使用可能な値が含まれます: 'Udp'、'Tcp'</span><span class="sxs-lookup"><span data-stu-id="79a68-108">Possible values include: 'Udp', 'Tcp'</span></span></param>
        <param name="frontendPort"><span data-ttu-id="79a68-109">外部エンドポイントのポートです。</span><span class="sxs-lookup"><span data-stu-id="79a68-109">The port for the external endpoint.</span></span> <span data-ttu-id="79a68-110">各規則のポート番号は、ロード バランサー内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="79a68-110">Port numbers for each Rule must be unique within the Load Balancer.</span></span>
            <span data-ttu-id="79a68-111">許容される値の範囲は 1 ~ 65534 です。</span><span class="sxs-lookup"><span data-stu-id="79a68-111">Acceptable values range from 1 to 65534.</span></span></param>
        <param name="backendPort"><span data-ttu-id="79a68-112">内部エンドポイントで使用されるポートです。</span><span class="sxs-lookup"><span data-stu-id="79a68-112">The port used for the internal endpoint.</span></span>
            <span data-ttu-id="79a68-113">許容される値の範囲は 1 ~ 65535 です。</span><span class="sxs-lookup"><span data-stu-id="79a68-113">Acceptable values range from 1 to 65535.</span></span></param>
        <param name="idleTimeoutInMinutes"><span data-ttu-id="79a68-114">TCP アイドル接続のタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="79a68-114">The timeout for the TCP idle connection.</span></span> <span data-ttu-id="79a68-115">値は、4 ~ 30 分間に設定できます。</span><span class="sxs-lookup"><span data-stu-id="79a68-115">The value can be set between 4 and 30 minutes.</span></span> <span data-ttu-id="79a68-116">既定値は、4 分です。</span><span class="sxs-lookup"><span data-stu-id="79a68-116">The default value is 4 minutes.</span></span> <span data-ttu-id="79a68-117">この要素は、プロトコルが TCP に設定されている場合にのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="79a68-117">This element is only used when the protocol is set to TCP.</span></span></param>
        <param name="enableFloatingIP"><span data-ttu-id="79a68-118">SQL AlwaysOn 可用性グループの構成に必要な floating IP 機能用に仮想マシンのエンドポイントを構成します。</span><span class="sxs-lookup"><span data-stu-id="79a68-118">Configures a virtual machine's endpoint for the floating IP capability required to configure a SQL AlwaysOn Availability Group.</span></span> <span data-ttu-id="79a68-119">SQL server で SQL AlwaysOn 可用性グループを使用する場合、この設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="79a68-119">This setting is required when using the SQL AlwaysOn Availability Groups in SQL server.</span></span> <span data-ttu-id="79a68-120">エンドポイントを作成した後、この設定を変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="79a68-120">This setting can't be changed after you create the endpoint.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="79a68-121">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="79a68-121">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="79a68-122">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="79a68-122">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="79a68-123">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="79a68-123">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="79a68-124">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="79a68-124">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="79a68-125">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="79a68-125">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="79a68-126">InboundNatRuleInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="79a68-126">Initializes a new instance of the InboundNatRuleInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner BackendIPConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner BackendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfiguration As NetworkInterfaceIPConfigurationInner" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfiguration : Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79a68-127">VM のネットワーク インターフェイスで定義されているプライベート IP アドレスへの参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="79a68-127">Gets a reference to a private IP address defined on a network interface of a VM.</span></span> <span data-ttu-id="79a68-128">各フロント エンド IP 構成のフロント エンド ポートに送信されるトラフィックは、バックアップされた ip アドレスに転送されます。</span><span class="sxs-lookup"><span data-stu-id="79a68-128">Traffic sent to the frontend port of each of the frontend IP configurations is forwarded to the backed IP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="79a68-129">取得または内部エンドポイントで使用されるポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="79a68-129">Gets or sets the port used for the internal endpoint.</span></span> <span data-ttu-id="79a68-130">許容される値の範囲は 1 ~ 65535 です。</span><span class="sxs-lookup"><span data-stu-id="79a68-130">Acceptable values range from 1 to 65535.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFloatingIP">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableFloatingIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableFloatingIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.EnableFloatingIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFloatingIP As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableFloatingIP : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.EnableFloatingIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="79a68-131">取得または設定は、SQL AlwaysOn 可用性グループの構成に必要な floating IP 機能用に仮想マシンのエンドポイントを構成します。</span><span class="sxs-lookup"><span data-stu-id="79a68-131">Gets or sets configures a virtual machine's endpoint for the floating IP capability required to configure a SQL AlwaysOn Availability Group.</span></span> <span data-ttu-id="79a68-132">SQL server で SQL AlwaysOn 可用性グループを使用する場合、この設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="79a68-132">This setting is required when using the SQL AlwaysOn Availability Groups in SQL server.</span></span> <span data-ttu-id="79a68-133">エンドポイントを作成した後、この設定を変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="79a68-133">This setting can't be changed after you create the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Etag" />
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
            <span data-ttu-id="79a68-134">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="79a68-134">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendIPConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79a68-135">取得またはフロント エンド IP アドレスへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="79a68-135">Gets or sets a reference to frontend IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.FrontendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="79a68-136">取得または外部エンドポイントのポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="79a68-136">Gets or sets the port for the external endpoint.</span></span> <span data-ttu-id="79a68-137">各規則のポート番号は、ロード バランサー内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="79a68-137">Port numbers for each Rule must be unique within the Load Balancer.</span></span> <span data-ttu-id="79a68-138">許容される値の範囲は 1 ~ 65534 です。</span><span class="sxs-lookup"><span data-stu-id="79a68-138">Acceptable values range from 1 to 65534.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="79a68-139">取得または TCP アイドル接続のタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="79a68-139">Gets or sets the timeout for the TCP idle connection.</span></span> <span data-ttu-id="79a68-140">値は、4 ~ 30 分間に設定できます。</span><span class="sxs-lookup"><span data-stu-id="79a68-140">The value can be set between 4 and 30 minutes.</span></span> <span data-ttu-id="79a68-141">既定値は、4 分です。</span><span class="sxs-lookup"><span data-stu-id="79a68-141">The default value is 4 minutes.</span></span>
            <span data-ttu-id="79a68-142">この要素は、プロトコルが TCP に設定されている場合にのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="79a68-142">This element is only used when the protocol is set to TCP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="79a68-143">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="79a68-143">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="79a68-144">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="79a68-144">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="79a68-145">取得またはエンドポイントのトランスポート プロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="79a68-145">Gets or sets the transport protocol for the endpoint.</span></span> <span data-ttu-id="79a68-146">使用可能な値が: 'Udp' または 'Tcp' です。</span><span class="sxs-lookup"><span data-stu-id="79a68-146">Possible values are: 'Udp' or 'Tcp'.</span></span> <span data-ttu-id="79a68-147">使用可能な値が含まれます: 'Udp'、'Tcp'</span><span class="sxs-lookup"><span data-stu-id="79a68-147">Possible values include: 'Udp', 'Tcp'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner.ProvisioningState" />
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
            <span data-ttu-id="79a68-148">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="79a68-148">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="79a68-149">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="79a68-149">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>