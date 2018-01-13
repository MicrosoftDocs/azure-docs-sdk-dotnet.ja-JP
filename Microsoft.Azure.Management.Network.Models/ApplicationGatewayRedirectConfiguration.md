<Type Name="ApplicationGatewayRedirectConfiguration" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayRedirectConfiguration : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayRedirectConfiguration extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayRedirectConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayRedirectConfiguration = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="3772b-101">アプリケーション ゲートウェイの構成をリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="3772b-101">Redirect configuration of an application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayRedirectConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.#ctor" />
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
            <span data-ttu-id="3772b-102">ApplicationGatewayRedirectConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3772b-102">Initializes a new instance of the ApplicationGatewayRedirectConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayRedirectConfiguration (string id = null, string redirectType = null, Microsoft.Azure.Management.Network.Models.SubResource targetListener = null, string targetUrl = null, Nullable&lt;bool&gt; includePath = null, Nullable&lt;bool&gt; includeQueryString = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; requestRoutingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; urlPathMaps = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; pathRules = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string redirectType, class Microsoft.Azure.Management.Network.Models.SubResource targetListener, string targetUrl, valuetype System.Nullable`1&lt;bool&gt; includePath, valuetype System.Nullable`1&lt;bool&gt; includeQueryString, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; requestRoutingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; urlPathMaps, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; pathRules, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.#ctor(System.String,System.String,Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional redirectType As String = null, Optional targetListener As SubResource = null, Optional targetUrl As String = null, Optional includePath As Nullable(Of Boolean) = null, Optional includeQueryString As Nullable(Of Boolean) = null, Optional requestRoutingRules As IList(Of SubResource) = null, Optional urlPathMaps As IList(Of SubResource) = null, Optional pathRules As IList(Of SubResource) = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration : string * string * Microsoft.Azure.Management.Network.Models.SubResource * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration (id, redirectType, targetListener, targetUrl, includePath, includeQueryString, requestRoutingRules, urlPathMaps, pathRules, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="redirectType" Type="System.String" />
        <Parameter Name="targetListener" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="targetUrl" Type="System.String" />
        <Parameter Name="includePath" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="includeQueryString" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requestRoutingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="urlPathMaps" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="pathRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3772b-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="3772b-103">Resource ID.</span></span></param>
        <param name="redirectType"><span data-ttu-id="3772b-104">Http リダイレクトの種類 - 永続的で、一時、Found、SeeOther をサポートします。</span><span class="sxs-lookup"><span data-stu-id="3772b-104">Supported http redirection types - Permanent, Temporary, Found, SeeOther.</span></span> <span data-ttu-id="3772b-105">使用可能な値が含まれます: '固定'、'が見つかりません'、'SeeOther'、'一時的な'</span><span class="sxs-lookup"><span data-stu-id="3772b-105">Possible values include: 'Permanent', 'Found', 'SeeOther', 'Temporary'</span></span></param>
        <param name="targetListener"><span data-ttu-id="3772b-106">要求をリダイレクトするリスナーへの参照。</span><span class="sxs-lookup"><span data-stu-id="3772b-106">Reference to a listener to redirect the request to.</span></span></param>
        <param name="targetUrl"><span data-ttu-id="3772b-107">要求をリダイレクトする Url。</span><span class="sxs-lookup"><span data-stu-id="3772b-107">Url to redirect the request to.</span></span></param>
        <param name="includePath"><span data-ttu-id="3772b-108">リダイレクト url のパスを含めます。</span><span class="sxs-lookup"><span data-stu-id="3772b-108">Include path in the redirected url.</span></span></param>
        <param name="includeQueryString"><span data-ttu-id="3772b-109">リダイレクト url にクエリ文字列を含めます。</span><span class="sxs-lookup"><span data-stu-id="3772b-109">Include query string in the redirected url.</span></span></param>
        <param name="requestRoutingRules"><span data-ttu-id="3772b-110">ルーティング構成を指定するリダイレクトを要求します。</span><span class="sxs-lookup"><span data-stu-id="3772b-110">Request routing specifying redirect configuration.</span></span></param>
        <param name="urlPathMaps"><span data-ttu-id="3772b-111">既定値を指定する Url パスのマップは、構成をリダイレクトします。</span><span class="sxs-lookup"><span data-stu-id="3772b-111">Url path maps specifying default redirect configuration.</span></span></param>
        <param name="pathRules"><span data-ttu-id="3772b-112">パス ルールを指定するリダイレクトを構成します。</span><span class="sxs-lookup"><span data-stu-id="3772b-112">Path rules specifying redirect configuration.</span></span></param>
        <param name="name"><span data-ttu-id="3772b-113">リソース グループ内で一意であるリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="3772b-113">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="3772b-114">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="3772b-114">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="3772b-115">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="3772b-115">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="type"><span data-ttu-id="3772b-116">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="3772b-116">Type of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="3772b-117">ApplicationGatewayRedirectConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3772b-117">Initializes a new instance of the ApplicationGatewayRedirectConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Etag" />
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
            <span data-ttu-id="3772b-118">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="3772b-118">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludePath">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IncludePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IncludePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludePath" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludePath As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IncludePath : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.includePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-119">取得または設定は、リダイレクトされる url のパスを含めます。</span><span class="sxs-lookup"><span data-stu-id="3772b-119">Gets or sets include path in the redirected url.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeQueryString">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IncludeQueryString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IncludeQueryString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludeQueryString" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeQueryString As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IncludeQueryString : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.IncludeQueryString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.includeQueryString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-120">取得または設定は、リダイレクトされる url にクエリ文字列を含めます。</span><span class="sxs-lookup"><span data-stu-id="3772b-120">Gets or sets include query string in the redirected url.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Name" />
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
            <span data-ttu-id="3772b-121">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3772b-121">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="3772b-122">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="3772b-122">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; PathRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; PathRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.PathRules" />
      <MemberSignature Language="VB.NET" Value="Public Property PathRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.PathRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.PathRules" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-123">取得またはリダイレクトの構成を指定するパスの規則を設定します。</span><span class="sxs-lookup"><span data-stu-id="3772b-123">Gets or sets path rules specifying redirect configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectType">
      <MemberSignature Language="C#" Value="public string RedirectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedirectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RedirectType" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectType As String" />
      <MemberSignature Language="F#" Value="member this.RedirectType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RedirectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redirectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-124">取得または、永続的で、一時、Found SeeOther サポートされている http リダイレクト型を設定します。</span><span class="sxs-lookup"><span data-stu-id="3772b-124">Gets or sets supported http redirection types - Permanent, Temporary, Found, SeeOther.</span></span> <span data-ttu-id="3772b-125">使用可能な値が含まれます: '固定'、'が見つかりません'、'SeeOther'、'一時的な'</span><span class="sxs-lookup"><span data-stu-id="3772b-125">Possible values include: 'Permanent', 'Found', 'SeeOther', 'Temporary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRoutingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; RequestRoutingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; RequestRoutingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RequestRoutingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestRoutingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.RequestRoutingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.RequestRoutingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestRoutingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-126">取得または要求で指定するルーティングのリダイレクト構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="3772b-126">Gets or sets request routing specifying redirect configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource TargetListener { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource TargetListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetListener" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetListener As SubResource" />
      <MemberSignature Language="F#" Value="member this.TargetListener : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetListener")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-127">取得または設定する要求をリダイレクトするリスナーへの参照。</span><span class="sxs-lookup"><span data-stu-id="3772b-127">Gets or sets reference to a listener to redirect the request to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetUrl">
      <MemberSignature Language="C#" Value="public string TargetUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetUrl As String" />
      <MemberSignature Language="F#" Value="member this.TargetUrl : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.TargetUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-128">取得またはへの要求をリダイレクトする url を設定します。</span><span class="sxs-lookup"><span data-stu-id="3772b-128">Gets or sets url to redirect the request to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.Type" />
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
            <span data-ttu-id="3772b-129">取得またはリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="3772b-129">Gets or sets type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UrlPathMaps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; UrlPathMaps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; UrlPathMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.UrlPathMaps" />
      <MemberSignature Language="VB.NET" Value="Public Property UrlPathMaps As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.UrlPathMaps : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayRedirectConfiguration.UrlPathMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.urlPathMaps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3772b-130">取得またはリダイレクトの既定の構成を指定する url パスのマップを設定します。</span><span class="sxs-lookup"><span data-stu-id="3772b-130">Gets or sets url path maps specifying default redirect configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>