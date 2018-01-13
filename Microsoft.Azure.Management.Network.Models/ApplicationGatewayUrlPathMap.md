<Type Name="ApplicationGatewayUrlPathMap" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayUrlPathMap : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayUrlPathMap extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayUrlPathMap&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayUrlPathMap = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="30cbf-101">UrlPathMaps は、PathBasedRouting のバックエンド マッピング情報を url パスを付けます。</span><span class="sxs-lookup"><span data-stu-id="30cbf-101">UrlPathMaps give a url path to the backend mapping information for PathBasedRouting.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayUrlPathMap ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.#ctor" />
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
            <span data-ttu-id="30cbf-102">ApplicationGatewayUrlPathMap クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-102">Initializes a new instance of the ApplicationGatewayUrlPathMap class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayUrlPathMap (string id = null, Microsoft.Azure.Management.Network.Models.SubResource defaultBackendAddressPool = null, Microsoft.Azure.Management.Network.Models.SubResource defaultBackendHttpSettings = null, Microsoft.Azure.Management.Network.Models.SubResource defaultRedirectConfiguration = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt; pathRules = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.Network.Models.SubResource defaultBackendAddressPool, class Microsoft.Azure.Management.Network.Models.SubResource defaultBackendHttpSettings, class Microsoft.Azure.Management.Network.Models.SubResource defaultRedirectConfiguration, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt; pathRules, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.#ctor(System.String,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional defaultBackendAddressPool As SubResource = null, Optional defaultBackendHttpSettings As SubResource = null, Optional defaultRedirectConfiguration As SubResource = null, Optional pathRules As IList(Of ApplicationGatewayPathRule) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap : string * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap (id, defaultBackendAddressPool, defaultBackendHttpSettings, defaultRedirectConfiguration, pathRules, provisioningState, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="defaultBackendAddressPool" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="defaultBackendHttpSettings" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="defaultRedirectConfiguration" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="pathRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="30cbf-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="30cbf-103">Resource ID.</span></span></param>
        <param name="defaultBackendAddressPool"><span data-ttu-id="30cbf-104">バックエンド アドレス プールの既定のリソース URL パス マップします。</span><span class="sxs-lookup"><span data-stu-id="30cbf-104">Default backend address pool resource of URL path map.</span></span></param>
        <param name="defaultBackendHttpSettings"><span data-ttu-id="30cbf-105">バックエンド http 設定の既定のリソース URL パス マップします。</span><span class="sxs-lookup"><span data-stu-id="30cbf-105">Default backend http settings resource of URL path map.</span></span></param>
        <param name="defaultRedirectConfiguration"><span data-ttu-id="30cbf-106">既定値 URL パスのマップの構成リソースをリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="30cbf-106">Default redirect configuration resource of URL path map.</span></span></param>
        <param name="pathRules"><span data-ttu-id="30cbf-107">URL パスのマップのリソースのパスの規則。</span><span class="sxs-lookup"><span data-stu-id="30cbf-107">Path rule of URL path map resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="30cbf-108">バックエンド http 設定リソースのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="30cbf-108">Provisioning state of the backend http settings resource.</span></span> <span data-ttu-id="30cbf-109">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="30cbf-109">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="30cbf-110">リソース グループ内で一意であるリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="30cbf-110">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="30cbf-111">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="30cbf-111">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="30cbf-112">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-112">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="type"><span data-ttu-id="30cbf-113">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="30cbf-113">Type of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="30cbf-114">ApplicationGatewayUrlPathMap クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-114">Initializes a new instance of the ApplicationGatewayUrlPathMap class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultBackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource DefaultBackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource DefaultBackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.DefaultBackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultBackendAddressPool As SubResource" />
      <MemberSignature Language="F#" Value="member this.DefaultBackendAddressPool : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.DefaultBackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultBackendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30cbf-115">取得または URL パスのマップの既定のバックエンド アドレス プールのリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-115">Gets or sets default backend address pool resource of URL path map.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultBackendHttpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource DefaultBackendHttpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource DefaultBackendHttpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.DefaultBackendHttpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultBackendHttpSettings As SubResource" />
      <MemberSignature Language="F#" Value="member this.DefaultBackendHttpSettings : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.DefaultBackendHttpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultBackendHttpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30cbf-116">取得または URL パスのマップの既定のバックエンド http 設定のリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-116">Gets or sets default backend http settings resource of URL path map.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRedirectConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource DefaultRedirectConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource DefaultRedirectConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.DefaultRedirectConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRedirectConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.DefaultRedirectConfiguration : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.DefaultRedirectConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultRedirectConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30cbf-117">取得または URL パスのマップの既定のリダイレクトの構成リソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-117">Gets or sets default redirect configuration resource of URL path map.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.Etag" />
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
            <span data-ttu-id="30cbf-118">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="30cbf-118">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.Name" />
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
            <span data-ttu-id="30cbf-119">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-119">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="30cbf-120">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="30cbf-120">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt; PathRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt; PathRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.PathRules" />
      <MemberSignature Language="VB.NET" Value="Public Property PathRules As IList(Of ApplicationGatewayPathRule)" />
      <MemberSignature Language="F#" Value="member this.PathRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.PathRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pathRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayPathRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30cbf-121">取得または URL パスのマップのリソースのパスの規則を設定します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-121">Gets or sets path rule of URL path map resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.ProvisioningState" />
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
            <span data-ttu-id="30cbf-122">取得またはバックエンド http 設定リソースのプロビジョニング状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-122">Gets or sets provisioning state of the backend http settings resource.</span></span> <span data-ttu-id="30cbf-123">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="30cbf-123">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayUrlPathMap.Type" />
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
            <span data-ttu-id="30cbf-124">取得またはリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="30cbf-124">Gets or sets type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>