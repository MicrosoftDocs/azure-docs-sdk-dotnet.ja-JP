<Type Name="NetworkSecurityGroup" FullName="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroup : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroup extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroup&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroup = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="614e8-101">NetworkSecurityGroup リソースです。</span><span class="sxs-lookup"><span data-stu-id="614e8-101">NetworkSecurityGroup resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.#ctor" />
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
            <span data-ttu-id="614e8-102">NetworkSecurityGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="614e8-102">Initializes a new instance of the NetworkSecurityGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroup (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; securityRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; defaultSecurityRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; networkInterfaces = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; securityRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; defaultSecurityRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; networkInterfaces, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SecurityRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SecurityRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.NetworkInterface},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Subnet},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional securityRules As IList(Of SecurityRule) = null, Optional defaultSecurityRules As IList(Of SecurityRule) = null, Optional networkInterfaces As IList(Of NetworkInterface) = null, Optional subnets As IList(Of Subnet) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="new Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup (id, name, type, location, tags, securityRules, defaultSecurityRules, networkInterfaces, subnets, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="securityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;" />
        <Parameter Name="defaultSecurityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;" />
        <Parameter Name="networkInterfaces" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" />
        <Parameter Name="subnets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="614e8-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="614e8-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="614e8-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="614e8-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="614e8-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="614e8-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="614e8-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="614e8-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="614e8-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="614e8-107">Resource tags.</span></span></param>
        <param name="securityRules"><span data-ttu-id="614e8-108">ネットワーク セキュリティ グループのセキュリティ規則のコレクション。</span><span class="sxs-lookup"><span data-stu-id="614e8-108">A collection of security rules of the network security group.</span></span></param>
        <param name="defaultSecurityRules"><span data-ttu-id="614e8-109">ネットワーク セキュリティ グループの既定のセキュリティの規則。</span><span class="sxs-lookup"><span data-stu-id="614e8-109">The default security rules of network security group.</span></span></param>
        <param name="networkInterfaces"><span data-ttu-id="614e8-110">ネットワーク インターフェイスへの参照のコレクション。</span><span class="sxs-lookup"><span data-stu-id="614e8-110">A collection of references to network interfaces.</span></span></param>
        <param name="subnets"><span data-ttu-id="614e8-111">サブネットへの参照のコレクション。</span><span class="sxs-lookup"><span data-stu-id="614e8-111">A collection of references to subnets.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="614e8-112">リソースのネットワーク セキュリティ グループ リソース GUID プロパティです。</span><span class="sxs-lookup"><span data-stu-id="614e8-112">The resource GUID property of the network security group resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="614e8-113">パブリック IP リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="614e8-113">The provisioning state of the public IP resource.</span></span> <span data-ttu-id="614e8-114">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="614e8-114">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="614e8-115">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="614e8-115">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="614e8-116">NetworkSecurityGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="614e8-116">Initializes a new instance of the NetworkSecurityGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; DefaultSecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; DefaultSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.DefaultSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultSecurityRules As IList(Of SecurityRule)" />
      <MemberSignature Language="F#" Value="member this.DefaultSecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.DefaultSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultSecurityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="614e8-117">取得または既定のネットワーク セキュリティ グループのセキュリティの規則を設定します。</span><span class="sxs-lookup"><span data-stu-id="614e8-117">Gets or sets the default security rules of network security group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.Etag" />
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
            <span data-ttu-id="614e8-118">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="614e8-118">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; NetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterface&gt; NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaces As IList(Of NetworkInterface)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;" Usage="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkInterfaces")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="614e8-119">ネットワーク インターフェイスへの参照のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="614e8-119">Gets a collection of references to network interfaces.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.ProvisioningState" />
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
            <span data-ttu-id="614e8-120">取得またはパブリック IP リソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="614e8-120">Gets or sets the provisioning state of the public IP resource.</span></span>
            <span data-ttu-id="614e8-121">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="614e8-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.ResourceGuid" />
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
            <span data-ttu-id="614e8-122">取得またはリソースのネットワーク セキュリティ グループ リソースの GUID プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="614e8-122">Gets or sets the resource GUID property of the network security group resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; SecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; SecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.SecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityRules As IList(Of SecurityRule)" />
      <MemberSignature Language="F#" Value="member this.SecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.SecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.securityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="614e8-123">取得またはネットワーク セキュリティ グループのセキュリティ規則のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="614e8-123">Gets or sets a collection of security rules of the network security group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subnets As IList(Of Subnet)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="614e8-124">サブネットへの参照のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="614e8-124">Gets a collection of references to subnets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>