<Type Name="ApplicationGatewaySslCertificate" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate">
  <TypeSignature Language="C#" Value="public class ApplicationGatewaySslCertificate : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewaySslCertificate extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewaySslCertificate&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaySslCertificate = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="6fdde-101">Application gateway の SSL 証明書。</span><span class="sxs-lookup"><span data-stu-id="6fdde-101">SSL certificates of an application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.#ctor" />
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
            <span data-ttu-id="6fdde-102">ApplicationGatewaySslCertificate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-102">Initializes a new instance of the ApplicationGatewaySslCertificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslCertificate (string id = null, string data = null, string password = null, string publicCertData = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string data, string password, string publicCertData, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional data As String = null, Optional password As String = null, Optional publicCertData As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate (id, data, password, publicCertData, provisioningState, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="publicCertData" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="6fdde-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="6fdde-103">Resource ID.</span></span></param>
        <param name="data"><span data-ttu-id="6fdde-104">Base 64 でエンコードされた pfx の証明書です。</span><span class="sxs-lookup"><span data-stu-id="6fdde-104">Base-64 encoded pfx certificate.</span></span> <span data-ttu-id="6fdde-105">PUT 要求にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-105">Only applicable in PUT Request.</span></span></param>
        <param name="password"><span data-ttu-id="6fdde-106">データで指定された pfx ファイルのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="6fdde-106">Password for the pfx file specified in data.</span></span>
            <span data-ttu-id="6fdde-107">PUT 要求でのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-107">Only applicable in PUT request.</span></span></param>
        <param name="publicCertData"><span data-ttu-id="6fdde-108">Base 64 エンコードのデータで指定された pfx に対応するパブリック証明書データです。</span><span class="sxs-lookup"><span data-stu-id="6fdde-108">Base-64 encoded Public cert data corresponding to pfx specified in data.</span></span> <span data-ttu-id="6fdde-109">GET 要求にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-109">Only applicable in GET request.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="6fdde-110">指定できる値は、SSL 証明書のリソースのプロビジョニング状態: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="6fdde-110">Provisioning state of the SSL certificate resource Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="6fdde-111">リソース グループ内で一意であるリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="6fdde-111">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="6fdde-112">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-112">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="6fdde-113">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-113">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="type"><span data-ttu-id="6fdde-114">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="6fdde-114">Type of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="6fdde-115">ApplicationGatewaySslCertificate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-115">Initializes a new instance of the ApplicationGatewaySslCertificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fdde-116">取得または base 64 でエンコードされた pfx の証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-116">Gets or sets base-64 encoded pfx certificate.</span></span> <span data-ttu-id="6fdde-117">PUT 要求にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-117">Only applicable in PUT Request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Etag" />
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
            <span data-ttu-id="6fdde-118">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="6fdde-118">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Name" />
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
            <span data-ttu-id="6fdde-119">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-119">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="6fdde-120">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-120">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fdde-121">取得またはデータに指定された pfx ファイルのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-121">Gets or sets password for the pfx file specified in data.</span></span> <span data-ttu-id="6fdde-122">PUT 要求でのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-122">Only applicable in PUT request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.ProvisioningState" />
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
            <span data-ttu-id="6fdde-123">SSL のプロビジョニング状態を取得または設定可能な値はリソースの証明書: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="6fdde-123">Gets or sets provisioning state of the SSL certificate resource Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicCertData">
      <MemberSignature Language="C#" Value="public string PublicCertData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicCertData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.PublicCertData" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicCertData As String" />
      <MemberSignature Language="F#" Value="member this.PublicCertData : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.PublicCertData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicCertData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fdde-124">取得またはデータに指定された pfx に対応するデータを base 64 でエンコードされたパブリック証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-124">Gets or sets base-64 encoded Public cert data corresponding to pfx specified in data.</span></span> <span data-ttu-id="6fdde-125">GET 要求にのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="6fdde-125">Only applicable in GET request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslCertificate.Type" />
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
            <span data-ttu-id="6fdde-126">取得またはリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6fdde-126">Gets or sets type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>