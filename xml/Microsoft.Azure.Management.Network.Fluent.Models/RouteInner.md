<Type Name="RouteInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner">
  <TypeSignature Language="C#" Value="public class RouteInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RouteInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RouteInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type RouteInner = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="c30d2-101">ルート リソース</span><span class="sxs-lookup"><span data-stu-id="c30d2-101">Route resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c30d2-102">RouteInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-102">Initializes a new instance of the RouteInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteInner (string nextHopType, string id = null, string addressPrefix = null, string nextHopIpAddress = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextHopType, string id, string addressPrefix, string nextHopIpAddress, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nextHopType As String, Optional id As String = null, Optional addressPrefix As String = null, Optional nextHopIpAddress As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.RouteInner : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.RouteInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.RouteInner (nextHopType, id, addressPrefix, nextHopIpAddress, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextHopType" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="addressPrefix" Type="System.String" />
        <Parameter Name="nextHopIpAddress" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nextHopType"><span data-ttu-id="c30d2-103">パケットの送信先となる Azure ホップの種類。</span><span class="sxs-lookup"><span data-stu-id="c30d2-103">The type of Azure hop the packet should be sent to.</span></span> <span data-ttu-id="c30d2-104">使用可能な値が: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance' および 'None' です。</span><span class="sxs-lookup"><span data-stu-id="c30d2-104">Possible values are: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', and 'None'.</span></span> <span data-ttu-id="c30d2-105">使用可能な値が含まれます: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance'、'None'</span><span class="sxs-lookup"><span data-stu-id="c30d2-105">Possible values include: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', 'None'</span></span></param>
        <param name="id">To be added.</param>
        <param name="addressPrefix"><span data-ttu-id="c30d2-106">ルートが適用される宛先の CIDR です。</span><span class="sxs-lookup"><span data-stu-id="c30d2-106">The destination CIDR to which the route applies.</span></span></param>
        <param name="nextHopIpAddress"><span data-ttu-id="c30d2-107">IP アドレス パケットを転送する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c30d2-107">The IP address packets should be forwarded to.</span></span> <span data-ttu-id="c30d2-108">次ホップの値は次のホップの種類が VirtualAppliance がルートでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="c30d2-108">Next hop values are only allowed in routes where the next hop type is VirtualAppliance.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="c30d2-109">リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="c30d2-109">The provisioning state of the resource.</span></span> <span data-ttu-id="c30d2-110">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="c30d2-110">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="c30d2-111">リソース グループ内で一意であるリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="c30d2-111">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="c30d2-112">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="c30d2-112">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="c30d2-113">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-113">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="c30d2-114">RouteInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-114">Initializes a new instance of the RouteInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressPrefix">
      <MemberSignature Language="C#" Value="public string AddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.AddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.AddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.addressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c30d2-115">取得またはルートが適用される宛先の CIDR を設定します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-115">Gets or sets the destination CIDR to which the route applies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.Etag" />
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
            <span data-ttu-id="c30d2-116">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="c30d2-116">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.Name" />
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
            <span data-ttu-id="c30d2-117">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-117">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="c30d2-118">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="c30d2-118">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIpAddress">
      <MemberSignature Language="C#" Value="public string NextHopIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.NextHopIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.NextHopIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.NextHopIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextHopIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c30d2-119">取得またはにパケットを転送するか、IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-119">Gets or sets the IP address packets should be forwarded to.</span></span> <span data-ttu-id="c30d2-120">次ホップの値は次のホップの種類が VirtualAppliance がルートでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="c30d2-120">Next hop values are only allowed in routes where the next hop type is VirtualAppliance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopType">
      <MemberSignature Language="C#" Value="public string NextHopType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.NextHopType" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopType As String" />
      <MemberSignature Language="F#" Value="member this.NextHopType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.NextHopType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextHopType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c30d2-121">取得またはにパケットを送信するか Azure ホップの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-121">Gets or sets the type of Azure hop the packet should be sent to.</span></span>
            <span data-ttu-id="c30d2-122">使用可能な値が: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance' および 'None' です。</span><span class="sxs-lookup"><span data-stu-id="c30d2-122">Possible values are: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', and 'None'.</span></span> <span data-ttu-id="c30d2-123">使用可能な値が含まれます: 'VirtualNetworkGateway'、'VnetLocal'、'Internet'、'VirtualAppliance'、'None'</span><span class="sxs-lookup"><span data-stu-id="c30d2-123">Possible values include: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', 'None'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.ProvisioningState" />
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
            <span data-ttu-id="c30d2-124">取得またはリソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-124">Gets or sets the provisioning state of the resource.</span></span> <span data-ttu-id="c30d2-125">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="c30d2-125">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.RouteInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routeInner.Validate " />
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
            <span data-ttu-id="c30d2-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c30d2-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c30d2-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c30d2-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>