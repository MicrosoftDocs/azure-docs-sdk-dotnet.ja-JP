<Type Name="ApplicationGatewayRequestRoutingRule" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayRequestRoutingRule : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayRequestRoutingRule extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayRequestRoutingRule&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayRequestRoutingRule = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="3c992-101">アプリケーション ゲートウェイのルーティング規則を要求します。</span><span class="sxs-lookup"><span data-stu-id="3c992-101">Request routing rule of an application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayRequestRoutingRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.#ctor" />
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
            <span data-ttu-id="3c992-102">ApplicationGatewayRequestRoutingRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3c992-102">Initializes a new instance of the ApplicationGatewayRequestRoutingRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayRequestRoutingRule (string id = null, string ruleType = null, Microsoft.Azure.Management.Network.Models.SubResource backendAddressPool = null, Microsoft.Azure.Management.Network.Models.SubResource backendHttpSettings = null, Microsoft.Azure.Management.Network.Models.SubResource httpListener = null, Microsoft.Azure.Management.Network.Models.SubResource urlPathMap = null, Microsoft.Azure.Management.Network.Models.SubResource redirectConfiguration = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string ruleType, class Microsoft.Azure.Management.Network.Models.SubResource backendAddressPool, class Microsoft.Azure.Management.Network.Models.SubResource backendHttpSettings, class Microsoft.Azure.Management.Network.Models.SubResource httpListener, class Microsoft.Azure.Management.Network.Models.SubResource urlPathMap, class Microsoft.Azure.Management.Network.Models.SubResource redirectConfiguration, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.#ctor(System.String,System.String,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional ruleType As String = null, Optional backendAddressPool As SubResource = null, Optional backendHttpSettings As SubResource = null, Optional httpListener As SubResource = null, Optional urlPathMap As SubResource = null, Optional redirectConfiguration As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule : string * string * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule (id, ruleType, backendAddressPool, backendHttpSettings, httpListener, urlPathMap, redirectConfiguration, provisioningState, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="ruleType" Type="System.String" />
        <Parameter Name="backendAddressPool" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="backendHttpSettings" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="httpListener" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="urlPathMap" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="redirectConfiguration" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3c992-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="3c992-103">Resource ID.</span></span></param>
        <param name="ruleType"><span data-ttu-id="3c992-104">ルールの種類。</span><span class="sxs-lookup"><span data-stu-id="3c992-104">Rule type.</span></span> <span data-ttu-id="3c992-105">使用可能な値が含まれます: 'Basic'、'PathBasedRouting'</span><span class="sxs-lookup"><span data-stu-id="3c992-105">Possible values include: 'Basic', 'PathBasedRouting'</span></span></param>
        <param name="backendAddressPool"><span data-ttu-id="3c992-106">アプリケーション ゲートウェイのバックエンド アドレス プール リソース。</span><span class="sxs-lookup"><span data-stu-id="3c992-106">Backend address pool resource of the application gateway.</span></span> </param>
        <param name="backendHttpSettings"><span data-ttu-id="3c992-107">アプリケーション ゲートウェイのフロント エンド ポート リソースです。</span><span class="sxs-lookup"><span data-stu-id="3c992-107">Frontend port resource of the application gateway.</span></span></param>
        <param name="httpListener"><span data-ttu-id="3c992-108">アプリケーション ゲートウェイの http リスナー リソースです。</span><span class="sxs-lookup"><span data-stu-id="3c992-108">Http listener resource of the application gateway.</span></span> </param>
        <param name="urlPathMap"><span data-ttu-id="3c992-109">アプリケーション ゲートウェイの URL パスのマップのリソース。</span><span class="sxs-lookup"><span data-stu-id="3c992-109">URL path map resource of the application gateway.</span></span></param>
        <param name="redirectConfiguration"><span data-ttu-id="3c992-110">アプリケーション ゲートウェイの構成リソースをリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="3c992-110">Redirect configuration resource of the application gateway.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="3c992-111">要求のルーティング規則リソースのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="3c992-111">Provisioning state of the request routing rule resource.</span></span> <span data-ttu-id="3c992-112">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="3c992-112">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="3c992-113">リソース グループ内で一意であるリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="3c992-113">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="3c992-114">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="3c992-114">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="3c992-115">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="3c992-115">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="type"><span data-ttu-id="3c992-116">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="3c992-116">Type of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="3c992-117">ApplicationGatewayRequestRoutingRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3c992-117">Initializes a new instance of the ApplicationGatewayRequestRoutingRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource BackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource BackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.BackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPool As SubResource" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPool : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.BackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c992-118">取得またはアプリケーション ゲートウェイのバックエンド アドレス プールのリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-118">Gets or sets backend address pool resource of the application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendHttpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource BackendHttpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource BackendHttpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.BackendHttpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendHttpSettings As SubResource" />
      <MemberSignature Language="F#" Value="member this.BackendHttpSettings : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.BackendHttpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendHttpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c992-119">取得またはアプリケーション ゲートウェイのフロント エンド ポート リソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-119">Gets or sets frontend port resource of the application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.Etag" />
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
            <span data-ttu-id="3c992-120">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="3c992-120">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource HttpListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource HttpListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.HttpListener" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpListener As SubResource" />
      <MemberSignature Language="F#" Value="member this.HttpListener : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.HttpListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpListener")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c992-121">取得またはアプリケーション ゲートウェイの http リスナー リソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-121">Gets or sets http listener resource of the application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.Name" />
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
            <span data-ttu-id="3c992-122">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-122">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="3c992-123">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="3c992-123">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.ProvisioningState" />
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
            <span data-ttu-id="3c992-124">取得または要求ルーティング ルールのリソースのプロビジョニング状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-124">Gets or sets provisioning state of the request routing rule resource.</span></span> <span data-ttu-id="3c992-125">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="3c992-125">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource RedirectConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource RedirectConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.RedirectConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectConfiguration As SubResource" />
      <MemberSignature Language="F#" Value="member this.RedirectConfiguration : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.RedirectConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redirectConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c992-126">取得またはアプリケーション ゲートウェイの構成リソースのリダイレクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-126">Gets or sets redirect configuration resource of the application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleType">
      <MemberSignature Language="C#" Value="public string RuleType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.RuleType" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleType As String" />
      <MemberSignature Language="F#" Value="member this.RuleType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.RuleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ruleType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c992-127">取得または規則の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-127">Gets or sets rule type.</span></span> <span data-ttu-id="3c992-128">使用可能な値が含まれます: 'Basic'、'PathBasedRouting'</span><span class="sxs-lookup"><span data-stu-id="3c992-128">Possible values include: 'Basic', 'PathBasedRouting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.Type" />
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
            <span data-ttu-id="3c992-129">取得またはリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-129">Gets or sets type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UrlPathMap">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource UrlPathMap { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource UrlPathMap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.UrlPathMap" />
      <MemberSignature Language="VB.NET" Value="Public Property UrlPathMap As SubResource" />
      <MemberSignature Language="F#" Value="member this.UrlPathMap : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRequestRoutingRule.UrlPathMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.urlPathMap")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c992-130">取得またはアプリケーション ゲートウェイの URL パス マップのリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="3c992-130">Gets or sets URL path map resource of the application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>