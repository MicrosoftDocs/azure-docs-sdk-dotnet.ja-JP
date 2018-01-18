<Type Name="LoadBalancingRuleInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner">
  <TypeSignature Language="C#" Value="public class LoadBalancingRuleInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LoadBalancingRuleInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner" />
  <TypeSignature Language="VB.NET" Value="Public Class LoadBalancingRuleInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type LoadBalancingRuleInner = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="f40b7-101">ロード バランサーのルールを分散 loag です。</span><span class="sxs-lookup"><span data-stu-id="f40b7-101">A loag balancing rule for a load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancingRuleInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f40b7-102">LoadBalancingRuleInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-102">Initializes a new instance of the LoadBalancingRuleInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancingRuleInner (string protocol, int frontendPort, string id = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource backendAddressPool = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource probe = null, string loadDistribution = null, Nullable&lt;int&gt; backendPort = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, Nullable&lt;bool&gt; enableFloatingIP = null, Nullable&lt;bool&gt; disableOutboundSnat = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, int32 frontendPort, string id, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource frontendIPConfiguration, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource backendAddressPool, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource probe, string loadDistribution, valuetype System.Nullable`1&lt;int32&gt; backendPort, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, valuetype System.Nullable`1&lt;bool&gt; enableFloatingIP, valuetype System.Nullable`1&lt;bool&gt; disableOutboundSnat, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.#ctor(System.String,System.Int32,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, frontendPort As Integer, Optional id As String = null, Optional frontendIPConfiguration As SubResource = null, Optional backendAddressPool As SubResource = null, Optional probe As SubResource = null, Optional loadDistribution As String = null, Optional backendPort As Nullable(Of Integer) = null, Optional idleTimeoutInMinutes As Nullable(Of Integer) = null, Optional enableFloatingIP As Nullable(Of Boolean) = null, Optional disableOutboundSnat As Nullable(Of Boolean) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner : string * int * string * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner (protocol, frontendPort, id, frontendIPConfiguration, backendAddressPool, probe, loadDistribution, backendPort, idleTimeoutInMinutes, enableFloatingIP, disableOutboundSnat, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="frontendPort" Type="System.Int32" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="frontendIPConfiguration" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="backendAddressPool" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="probe" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="loadDistribution" Type="System.String" />
        <Parameter Name="backendPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enableFloatingIP" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="disableOutboundSnat" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">To be added.</param>
        <param name="frontendPort">To be added.</param>
        <param name="id">To be added.</param>
        <param name="frontendIPConfiguration">To be added.</param>
        <param name="backendAddressPool">To be added.</param>
        <param name="probe">To be added.</param>
        <param name="loadDistribution">To be added.</param>
        <param name="backendPort">To be added.</param>
        <param name="idleTimeoutInMinutes">To be added.</param>
        <param name="enableFloatingIP">To be added.</param>
        <param name="disableOutboundSnat">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="name">To be added.</param>
        <param name="etag">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource BackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource BackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.BackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPool As SubResource" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPool : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.BackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f40b7-103">取得または Dip のプールへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-103">Gets or sets a reference to a pool of DIPs.</span></span> <span data-ttu-id="f40b7-104">受信トラフィックは、バックエンド ip アドレスで ip アドレスの間で分散ロードではランダムにします。</span><span class="sxs-lookup"><span data-stu-id="f40b7-104">Inbound traffic is randomly load balanced across IPs in the backend IPs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackendPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.BackendPort" />
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
            <span data-ttu-id="f40b7-105">取得またはエンドポイントの内部接続に使用するポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-105">Gets or sets the port used for internal connections on the endpoint.</span></span> <span data-ttu-id="f40b7-106">指定できる値は、1 ~ 65535 の間はします。</span><span class="sxs-lookup"><span data-stu-id="f40b7-106">Acceptable values are between 1 and 65535.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableOutboundSnat">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisableOutboundSnat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisableOutboundSnat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.DisableOutboundSnat" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableOutboundSnat As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisableOutboundSnat : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.DisableOutboundSnat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.disableOutboundSnat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFloatingIP">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableFloatingIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableFloatingIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.EnableFloatingIP" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFloatingIP As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableFloatingIP : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.EnableFloatingIP" />
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
            <span data-ttu-id="f40b7-107">取得または設定は、SQL AlwaysOn 可用性グループの構成に必要な floating IP 機能用に仮想マシンのエンドポイントを構成します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-107">Gets or sets configures a virtual machine's endpoint for the floating IP capability required to configure a SQL AlwaysOn Availability Group.</span></span> <span data-ttu-id="f40b7-108">SQL server で SQL AlwaysOn 可用性グループを使用する場合、この設定が必要です。</span><span class="sxs-lookup"><span data-stu-id="f40b7-108">This setting is required when using the SQL AlwaysOn Availability Groups in SQL server.</span></span> <span data-ttu-id="f40b7-109">エンドポイントを作成した後、この設定を変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="f40b7-109">This setting can't be changed after you create the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Etag" />
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
            <span data-ttu-id="f40b7-110">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="f40b7-110">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource FrontendIPConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.FrontendIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfiguration : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.FrontendIPConfiguration" />
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
            <span data-ttu-id="f40b7-111">取得またはフロント エンド IP アドレスへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-111">Gets or sets a reference to frontend IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPort">
      <MemberSignature Language="C#" Value="public int FrontendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.FrontendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPort : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.FrontendPort" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f40b7-112">取得または外部エンドポイントのポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-112">Gets or sets the port for the external endpoint.</span></span> <span data-ttu-id="f40b7-113">各規則のポート番号は、ロード バランサー内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f40b7-113">Port numbers for each Rule must be unique within the Load Balancer.</span></span> <span data-ttu-id="f40b7-114">指定できる値は、1 ~ 65,534 の範囲はします。</span><span class="sxs-lookup"><span data-stu-id="f40b7-114">Acceptable values are between 1 and 65534.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.IdleTimeoutInMinutes" />
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
            <span data-ttu-id="f40b7-115">取得または TCP アイドル接続のタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-115">Gets or sets the timeout for the TCP idle connection.</span></span> <span data-ttu-id="f40b7-116">値は、4 ~ 30 分間に設定できます。</span><span class="sxs-lookup"><span data-stu-id="f40b7-116">The value can be set between 4 and 30 minutes.</span></span> <span data-ttu-id="f40b7-117">既定値は、4 分です。</span><span class="sxs-lookup"><span data-stu-id="f40b7-117">The default value is 4 minutes.</span></span>
            <span data-ttu-id="f40b7-118">この要素は、プロトコルが TCP に設定されている場合にのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-118">This element is only used when the protocol is set to TCP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadDistribution">
      <MemberSignature Language="C#" Value="public string LoadDistribution { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoadDistribution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.LoadDistribution" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadDistribution As String" />
      <MemberSignature Language="F#" Value="member this.LoadDistribution : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.LoadDistribution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadDistribution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f40b7-119">取得または、この規則の負荷のディストリビューション ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-119">Gets or sets the load distribution policy for this rule.</span></span> <span data-ttu-id="f40b7-120">使用可能な値は 'Default'、'SourceIP' および 'SourceIPProtocol' です。</span><span class="sxs-lookup"><span data-stu-id="f40b7-120">Possible values are 'Default', 'SourceIP', and 'SourceIPProtocol'.</span></span> <span data-ttu-id="f40b7-121">使用可能な値が含まれます: 'Default'、'SourceIP'、'SourceIPProtocol'</span><span class="sxs-lookup"><span data-stu-id="f40b7-121">Possible values include: 'Default', 'SourceIP', 'SourceIPProtocol'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Name" />
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
            <span data-ttu-id="f40b7-122">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-122">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="f40b7-123">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="f40b7-123">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Probe { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Probe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Probe" />
      <MemberSignature Language="VB.NET" Value="Public Property Probe As SubResource" />
      <MemberSignature Language="F#" Value="member this.Probe : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Probe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probe")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f40b7-124">取得またはロード バランシング ルールで使用されるロード バランサーのプローブへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-124">Gets or sets the reference of the load balancer probe used by the load balancing rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Protocol" />
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
            <span data-ttu-id="f40b7-125">取得または外部エンドポイントのトランスポート プロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-125">Gets or sets the transport protocol for the external endpoint.</span></span>
            <span data-ttu-id="f40b7-126">可能な値は、'Udp' または 'Tcp' です。</span><span class="sxs-lookup"><span data-stu-id="f40b7-126">Possible values are 'Udp' or 'Tcp'.</span></span> <span data-ttu-id="f40b7-127">使用可能な値が含まれます: 'Udp'、'Tcp'</span><span class="sxs-lookup"><span data-stu-id="f40b7-127">Possible values include: 'Udp', 'Tcp'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.ProvisioningState" />
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
            <span data-ttu-id="f40b7-128">パブリック Ip リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-128">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="f40b7-129">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="f40b7-129">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="loadBalancingRuleInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f40b7-130">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f40b7-130">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f40b7-131">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f40b7-131">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>