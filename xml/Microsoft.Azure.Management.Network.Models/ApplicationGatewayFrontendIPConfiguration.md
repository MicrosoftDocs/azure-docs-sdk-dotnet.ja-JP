<Type Name="ApplicationGatewayFrontendIPConfiguration" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayFrontendIPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayFrontendIPConfiguration extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayFrontendIPConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayFrontendIPConfiguration = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="13629-101">アプリケーション ゲートウェイのフロント エンド IP 構成します。</span><span class="sxs-lookup"><span data-stu-id="13629-101">Frontend IP configuration of an application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFrontendIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.#ctor" />
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
            <span data-ttu-id="13629-102">ApplicationGatewayFrontendIPConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13629-102">Initializes a new instance of the ApplicationGatewayFrontendIPConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFrontendIPConfiguration (string id = null, string privateIPAddress = null, string privateIPAllocationMethod = null, Microsoft.Azure.Management.Network.Models.SubResource subnet = null, Microsoft.Azure.Management.Network.Models.SubResource publicIPAddress = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string privateIPAddress, string privateIPAllocationMethod, class Microsoft.Azure.Management.Network.Models.SubResource subnet, class Microsoft.Azure.Management.Network.Models.SubResource publicIPAddress, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional privateIPAddress As String = null, Optional privateIPAllocationMethod As String = null, Optional subnet As SubResource = null, Optional publicIPAddress As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration : string * string * string * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration (id, privateIPAddress, privateIPAllocationMethod, subnet, publicIPAddress, provisioningState, name, etag, type)" />
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
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="13629-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="13629-103">Resource ID.</span></span></param>
        <param name="privateIPAddress"><span data-ttu-id="13629-104">ネットワークの PrivateIPAddress インターフェイス IP 構成します。</span><span class="sxs-lookup"><span data-stu-id="13629-104">PrivateIPAddress of the network interface IP Configuration.</span></span></param>
        <param name="privateIPAllocationMethod"><span data-ttu-id="13629-105">PrivateIP 割り当て方法です。</span><span class="sxs-lookup"><span data-stu-id="13629-105">PrivateIP allocation method.</span></span> <span data-ttu-id="13629-106">使用可能な値が含まれます: 'Static'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="13629-106">Possible values include: 'Static', 'Dynamic'</span></span></param>
        <param name="subnet"><span data-ttu-id="13629-107">サブネットのリソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="13629-107">Reference of the subnet resource.</span></span></param>
        <param name="publicIPAddress"><span data-ttu-id="13629-108">パブリック Ip リソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="13629-108">Reference of the PublicIP resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="13629-109">パブリック IP リソースのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="13629-109">Provisioning state of the public IP resource.</span></span> <span data-ttu-id="13629-110">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="13629-110">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="13629-111">リソース グループ内で一意であるリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="13629-111">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="13629-112">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="13629-112">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="13629-113">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="13629-113">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="type"><span data-ttu-id="13629-114">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="13629-114">Type of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="13629-115">ApplicationGatewayFrontendIPConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13629-115">Initializes a new instance of the ApplicationGatewayFrontendIPConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Etag" />
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
            <span data-ttu-id="13629-116">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="13629-116">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Name" />
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
            <span data-ttu-id="13629-117">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="13629-117">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="13629-118">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="13629-118">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddress">
      <MemberSignature Language="C#" Value="public string PrivateIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.PrivateIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.PrivateIPAddress" />
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
            <span data-ttu-id="13629-119">取得またはネットワーク インターフェイス IP 構成の privateIPAddress を設定します。</span><span class="sxs-lookup"><span data-stu-id="13629-119">Gets or sets privateIPAddress of the network interface IP Configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAllocationMethod">
      <MemberSignature Language="C#" Value="public string PrivateIPAllocationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.PrivateIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAllocationMethod As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAllocationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.PrivateIPAllocationMethod" />
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
            <span data-ttu-id="13629-120">取得または privateIP 割り当て方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="13629-120">Gets or sets privateIP allocation method.</span></span> <span data-ttu-id="13629-121">使用可能な値が含まれます: 'Static'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="13629-121">Possible values include: 'Static', 'Dynamic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.ProvisioningState" />
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
            <span data-ttu-id="13629-122">取得またはパブリック IP リソースのプロビジョニング状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="13629-122">Gets or sets provisioning state of the public IP resource.</span></span> <span data-ttu-id="13629-123">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="13629-123">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource PublicIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource PublicIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.PublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddress As SubResource" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddress : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.PublicIPAddress" />
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
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13629-124">取得またはパブリック Ip リソースの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="13629-124">Gets or sets reference of the PublicIP resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As SubResource" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Subnet" />
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
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13629-125">取得またはサブネットのリソースの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="13629-125">Gets or sets reference of the subnet resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFrontendIPConfiguration.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13629-126">取得またはリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="13629-126">Gets or sets type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>