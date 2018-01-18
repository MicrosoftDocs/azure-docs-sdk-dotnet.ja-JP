<Type Name="IPConfiguration" FullName="Microsoft.Azure.Management.Network.Models.IPConfiguration">
  <TypeSignature Language="C#" Value="public class IPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IPConfiguration extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.IPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class IPConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type IPConfiguration = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="3ceeb-101">IP 構成</span><span class="sxs-lookup"><span data-stu-id="3ceeb-101">IP configuration</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IPConfiguration.#ctor" />
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
            <span data-ttu-id="3ceeb-102">Ip 構成クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-102">Initializes a new instance of the IPConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPConfiguration (string id = null, string privateIPAddress = null, string privateIPAllocationMethod = null, Microsoft.Azure.Management.Network.Models.Subnet subnet = null, Microsoft.Azure.Management.Network.Models.PublicIPAddress publicIPAddress = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string privateIPAddress, string privateIPAllocationMethod, class Microsoft.Azure.Management.Network.Models.Subnet subnet, class Microsoft.Azure.Management.Network.Models.PublicIPAddress publicIPAddress, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IPConfiguration.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet,Microsoft.Azure.Management.Network.Models.PublicIPAddress,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.IPConfiguration : string * string * string * Microsoft.Azure.Management.Network.Models.Subnet * Microsoft.Azure.Management.Network.Models.PublicIPAddress * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.IPConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.IPConfiguration (id, privateIPAddress, privateIPAllocationMethod, subnet, publicIPAddress, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="privateIPAddress" Type="System.String" />
        <Parameter Name="privateIPAllocationMethod" Type="System.String" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3ceeb-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="3ceeb-103">Resource ID.</span></span></param>
        <param name="privateIPAddress"><span data-ttu-id="3ceeb-104">IP 構成のプライベート IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-104">The private IP address of the IP configuration.</span></span></param>
        <param name="privateIPAllocationMethod"><span data-ttu-id="3ceeb-105">プライベート IP の割り当て方法です。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-105">The private IP allocation method.</span></span> <span data-ttu-id="3ceeb-106">可能な値は 'Static' および 'Dynamic' です。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-106">Possible values are 'Static' and 'Dynamic'.</span></span> <span data-ttu-id="3ceeb-107">使用可能な値が含まれます: 'Static'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="3ceeb-107">Possible values include: 'Static', 'Dynamic'</span></span></param>
        <param name="subnet"><span data-ttu-id="3ceeb-108">サブネットのリソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-108">The reference of the subnet resource.</span></span></param>
        <param name="publicIPAddress"><span data-ttu-id="3ceeb-109">パブリック IP リソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-109">The reference of the public IP resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="3ceeb-110">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-110">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="3ceeb-111">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-111">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="3ceeb-112">リソース グループ内で一意であるリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-112">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="3ceeb-113">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-113">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="3ceeb-114">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-114">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="3ceeb-115">Ip 構成クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-115">Initializes a new instance of the IPConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IPConfiguration.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IPConfiguration.Etag" />
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
            <span data-ttu-id="3ceeb-116">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-116">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IPConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IPConfiguration.Name" />
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
            <span data-ttu-id="3ceeb-117">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-117">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="3ceeb-118">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-118">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddress">
      <MemberSignature Language="C#" Value="public string PrivateIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IPConfiguration.PrivateIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IPConfiguration.PrivateIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ceeb-119">取得または IP 構成のプライベート IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-119">Gets or sets the private IP address of the IP configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAllocationMethod">
      <MemberSignature Language="C#" Value="public string PrivateIPAllocationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IPConfiguration.PrivateIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAllocationMethod As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAllocationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IPConfiguration.PrivateIPAllocationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAllocationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ceeb-120">取得またはプライベート IP の割り当て方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-120">Gets or sets the private IP allocation method.</span></span> <span data-ttu-id="3ceeb-121">可能な値は 'Static' および 'Dynamic' です。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-121">Possible values are 'Static' and 'Dynamic'.</span></span> <span data-ttu-id="3ceeb-122">使用可能な値が含まれます: 'Static'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="3ceeb-122">Possible values include: 'Static', 'Dynamic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IPConfiguration.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IPConfiguration.ProvisioningState" />
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
            <span data-ttu-id="3ceeb-123">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-123">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="3ceeb-124">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-124">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PublicIPAddress PublicIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PublicIPAddress PublicIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IPConfiguration.PublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddress As PublicIPAddress" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddress : Microsoft.Azure.Management.Network.Models.PublicIPAddress with get, set" Usage="Microsoft.Azure.Management.Network.Models.IPConfiguration.PublicIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ceeb-125">取得またはパブリック IP リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-125">Gets or sets the reference of the public IP resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.Subnet Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.Subnet Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IPConfiguration.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As Subnet" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Network.Models.Subnet with get, set" Usage="Microsoft.Azure.Management.Network.Models.IPConfiguration.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ceeb-126">取得またはサブネットのリソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ceeb-126">Gets or sets the reference of the subnet resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>