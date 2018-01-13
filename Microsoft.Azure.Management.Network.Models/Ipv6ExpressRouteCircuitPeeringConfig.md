<Type Name="Ipv6ExpressRouteCircuitPeeringConfig" FullName="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig">
  <TypeSignature Language="C#" Value="public class Ipv6ExpressRouteCircuitPeeringConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Ipv6ExpressRouteCircuitPeeringConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class Ipv6ExpressRouteCircuitPeeringConfig" />
  <TypeSignature Language="F#" Value="type Ipv6ExpressRouteCircuitPeeringConfig = class" />
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
            <span data-ttu-id="a44c0-101">IPv6 ピアリング構成が含まれています。</span><span class="sxs-lookup"><span data-stu-id="a44c0-101">Contains IPv6 peering config.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Ipv6ExpressRouteCircuitPeeringConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.#ctor" />
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
            <span data-ttu-id="a44c0-102">Ipv6ExpressRouteCircuitPeeringConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-102">Initializes a new instance of the Ipv6ExpressRouteCircuitPeeringConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Ipv6ExpressRouteCircuitPeeringConfig (string primaryPeerAddressPrefix = null, string secondaryPeerAddressPrefix = null, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig = null, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilter = null, string state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryPeerAddressPrefix, string secondaryPeerAddressPrefix, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilter, string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.#ctor(System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig,Microsoft.Azure.Management.Network.Models.RouteFilter,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig : string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig * Microsoft.Azure.Management.Network.Models.RouteFilter * string -&gt; Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig" Usage="new Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig (primaryPeerAddressPrefix, secondaryPeerAddressPrefix, microsoftPeeringConfig, routeFilter, state)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryPeerAddressPrefix" Type="System.String" />
        <Parameter Name="secondaryPeerAddressPrefix" Type="System.String" />
        <Parameter Name="microsoftPeeringConfig" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig" />
        <Parameter Name="routeFilter" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primaryPeerAddressPrefix"><span data-ttu-id="a44c0-103">プライマリ アドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="a44c0-103">The primary address prefix.</span></span></param>
        <param name="secondaryPeerAddressPrefix"><span data-ttu-id="a44c0-104">セカンダリ アドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="a44c0-104">The secondary address prefix.</span></span></param>
        <param name="microsoftPeeringConfig"><span data-ttu-id="a44c0-105">Microsoft ピアリング構成します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-105">The Microsoft peering configuration.</span></span></param>
        <param name="routeFilter"><span data-ttu-id="a44c0-106">RouteFilter リソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="a44c0-106">The reference of the RouteFilter resource.</span></span></param>
        <param name="state"><span data-ttu-id="a44c0-107">ピアリングの状態。</span><span class="sxs-lookup"><span data-stu-id="a44c0-107">The state of peering.</span></span> <span data-ttu-id="a44c0-108">使用可能な値が: 'Disabled'、'Enabled' です。</span><span class="sxs-lookup"><span data-stu-id="a44c0-108">Possible values are: 'Disabled' and 'Enabled'.</span></span> <span data-ttu-id="a44c0-109">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="a44c0-109">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <summary>
            <span data-ttu-id="a44c0-110">Ipv6ExpressRouteCircuitPeeringConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-110">Initializes a new instance of the Ipv6ExpressRouteCircuitPeeringConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftPeeringConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.MicrosoftPeeringConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftPeeringConfig As ExpressRouteCircuitPeeringConfig" />
      <MemberSignature Language="F#" Value="member this.MicrosoftPeeringConfig : Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig with get, set" Usage="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.MicrosoftPeeringConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="microsoftPeeringConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a44c0-111">取得または Microsoft ピアリング構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-111">Gets or sets the Microsoft peering configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string PrimaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.PrimaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.PrimaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryPeerAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a44c0-112">取得またはプライマリ アドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-112">Gets or sets the primary address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.RouteFilter RouteFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.RouteFilter RouteFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.RouteFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteFilter As RouteFilter" />
      <MemberSignature Language="F#" Value="member this.RouteFilter : Microsoft.Azure.Management.Network.Models.RouteFilter with get, set" Usage="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.RouteFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routeFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a44c0-113">取得または RouteFilter リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-113">Gets or sets the reference of the RouteFilter resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string SecondaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.SecondaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.SecondaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryPeerAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a44c0-114">取得またはセカンダリのアドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-114">Gets or sets the secondary address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a44c0-115">取得またはピアリングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a44c0-115">Gets or sets the state of peering.</span></span> <span data-ttu-id="a44c0-116">使用可能な値が: 'Disabled'、'Enabled' です。</span><span class="sxs-lookup"><span data-stu-id="a44c0-116">Possible values are: 'Disabled' and 'Enabled'.</span></span> <span data-ttu-id="a44c0-117">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="a44c0-117">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>