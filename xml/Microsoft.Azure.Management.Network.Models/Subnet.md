<Type Name="Subnet" FullName="Microsoft.Azure.Management.Network.Models.Subnet">
  <TypeSignature Language="C#" Value="public class Subnet : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Subnet extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.Subnet" />
  <TypeSignature Language="VB.NET" Value="Public Class Subnet&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Subnet = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="a2b08-101">仮想ネットワーク リソース内のサブネットです。</span><span class="sxs-lookup"><span data-stu-id="a2b08-101">Subnet in a virtual network resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Subnet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Subnet.#ctor" />
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
            <span data-ttu-id="a2b08-102">サブネット クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-102">Initializes a new instance of the Subnet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Subnet (string id = null, string addressPrefix = null, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup networkSecurityGroup = null, Microsoft.Azure.Management.Network.Models.RouteTable routeTable = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt; serviceEndpoints = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IPConfiguration&gt; ipConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt; resourceNavigationLinks = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string addressPrefix, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup networkSecurityGroup, class Microsoft.Azure.Management.Network.Models.RouteTable routeTable, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt; serviceEndpoints, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.IPConfiguration&gt; ipConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt; resourceNavigationLinks, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Subnet.#ctor(System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup,Microsoft.Azure.Management.Network.Models.RouteTable,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.IPConfiguration},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ResourceNavigationLink},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.Subnet : string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup * Microsoft.Azure.Management.Network.Models.RouteTable * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IPConfiguration&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.Subnet" Usage="new Microsoft.Azure.Management.Network.Models.Subnet (id, addressPrefix, networkSecurityGroup, routeTable, serviceEndpoints, ipConfigurations, resourceNavigationLinks, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="addressPrefix" Type="System.String" />
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
        <Parameter Name="routeTable" Type="Microsoft.Azure.Management.Network.Models.RouteTable" />
        <Parameter Name="serviceEndpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt;" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IPConfiguration&gt;" />
        <Parameter Name="resourceNavigationLinks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a2b08-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="a2b08-103">Resource ID.</span></span></param>
        <param name="addressPrefix"><span data-ttu-id="a2b08-104">サブネットのアドレス プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="a2b08-104">The address prefix for the subnet.</span></span></param>
        <param name="networkSecurityGroup"><span data-ttu-id="a2b08-105">NetworkSecurityGroup リソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="a2b08-105">The reference of the NetworkSecurityGroup resource.</span></span></param>
        <param name="routeTable"><span data-ttu-id="a2b08-106">RouteTable リソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="a2b08-106">The reference of the RouteTable resource.</span></span></param>
        <param name="serviceEndpoints"><span data-ttu-id="a2b08-107">サービス エンドポイントの配列。</span><span class="sxs-lookup"><span data-stu-id="a2b08-107">An array of service endpoints.</span></span></param>
        <param name="ipConfigurations"><span data-ttu-id="a2b08-108">サブネットを使用して、ネットワーク インターフェイス IP 構成への参照の配列を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-108">Gets an array of references to the network interface IP configurations using subnet.</span></span></param>
        <param name="resourceNavigationLinks"><span data-ttu-id="a2b08-109">サブネットを使用して外部リソースへの参照の配列を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-109">Gets an array of references to the external resources using subnet.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="a2b08-110">リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="a2b08-110">The provisioning state of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="a2b08-111">リソース グループ内で一意であるリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="a2b08-111">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="a2b08-112">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="a2b08-112">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="a2b08-113">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-113">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="a2b08-114">サブネット クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-114">Initializes a new instance of the Subnet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressPrefix">
      <MemberSignature Language="C#" Value="public string AddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.AddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.AddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="a2b08-115">取得またはサブネットのアドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-115">Gets or sets the address prefix for the subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.Etag" />
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
            <span data-ttu-id="a2b08-116">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="a2b08-116">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IPConfiguration&gt; IpConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.IPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpConfigurations As IList(Of IPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.Models.Subnet.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.IPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2b08-117">サブネットを使用して、ネットワーク インターフェイス IP 構成への参照の配列を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-117">Gets an array of references to the network interface IP configurations using subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.Name" />
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
            <span data-ttu-id="a2b08-118">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-118">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="a2b08-119">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="a2b08-119">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2b08-120">取得または NetworkSecurityGroup リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-120">Gets or sets the reference of the NetworkSecurityGroup resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.ProvisioningState" />
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
            <span data-ttu-id="a2b08-121">取得またはリソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-121">Gets or sets the provisioning state of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceNavigationLinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt; ResourceNavigationLinks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt; ResourceNavigationLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.ResourceNavigationLinks" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceNavigationLinks As IList(Of ResourceNavigationLink)" />
      <MemberSignature Language="F#" Value="member this.ResourceNavigationLinks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.ResourceNavigationLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceNavigationLinks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ResourceNavigationLink&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2b08-122">サブネットを使用して外部リソースへの参照の配列を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-122">Gets an array of references to the external resources using subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.RouteTable RouteTable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.RouteTable RouteTable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.RouteTable" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteTable As RouteTable" />
      <MemberSignature Language="F#" Value="member this.RouteTable : Microsoft.Azure.Management.Network.Models.RouteTable with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.RouteTable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeTable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteTable</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2b08-123">取得または RouteTable リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-123">Gets or sets the reference of the RouteTable resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt; ServiceEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt; ServiceEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Subnet.ServiceEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceEndpoints As IList(Of ServiceEndpointPropertiesFormat)" />
      <MemberSignature Language="F#" Value="member this.ServiceEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.Subnet.ServiceEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ServiceEndpointPropertiesFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2b08-124">取得またはサービス エンドポイントの配列を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2b08-124">Gets or sets an array of service endpoints.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>