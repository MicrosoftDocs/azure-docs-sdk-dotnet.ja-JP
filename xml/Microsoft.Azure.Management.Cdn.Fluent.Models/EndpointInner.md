<Type Name="EndpointInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner">
  <TypeSignature Language="C#" Value="public class EndpointInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EndpointInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner" />
  <TypeSignature Language="VB.NET" Value="Public Class EndpointInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type EndpointInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="83cb8-101">CDN エンドポイントは、origin、プロトコル、コンテンツのキャッシュおよび配信の動作などの構成情報が含まれている CDN プロファイル内のエンティティです。</span><span class="sxs-lookup"><span data-stu-id="83cb8-101">CDN endpoint is the entity within a CDN profile containing configuration information such as origin, protocol, content caching and delivery behavior.</span></span> <span data-ttu-id="83cb8-102">CDN エンドポイント URL の形式を使用して&lt;endpointname&gt;。 azureedge.net です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-102">The CDN endpoint uses the URL format &lt;endpointname&gt;.azureedge.net.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-103">EndpointInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-103">Initializes a new instance of the EndpointInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointInner (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt; origins, string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string originHostHeader = null, string originPath = null, System.Collections.Generic.IList&lt;string&gt; contentTypesToCompress = null, Nullable&lt;bool&gt; isCompressionEnabled = null, Nullable&lt;bool&gt; isHttpAllowed = null, Nullable&lt;bool&gt; isHttpsAllowed = null, Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; queryStringCachingBehavior = null, string optimizationType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters = null, string hostName = null, string resourceState = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt; origins, string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string originHostHeader, string originPath, class System.Collections.Generic.IList`1&lt;string&gt; contentTypesToCompress, valuetype System.Nullable`1&lt;bool&gt; isCompressionEnabled, valuetype System.Nullable`1&lt;bool&gt; isHttpAllowed, valuetype System.Nullable`1&lt;bool&gt; isHttpsAllowed, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; queryStringCachingBehavior, string optimizationType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters, string hostName, string resourceState, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (origins As IList(Of DeepCreatedOrigin), Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional originHostHeader As String = null, Optional originPath As String = null, Optional contentTypesToCompress As IList(Of String) = null, Optional isCompressionEnabled As Nullable(Of Boolean) = null, Optional isHttpAllowed As Nullable(Of Boolean) = null, Optional isHttpsAllowed As Nullable(Of Boolean) = null, Optional queryStringCachingBehavior As Nullable(Of QueryStringCachingBehavior) = null, Optional optimizationType As String = null, Optional geoFilters As IList(Of GeoFilter) = null, Optional hostName As String = null, Optional resourceState As String = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner (origins, location, id, name, type, tags, originHostHeader, originPath, contentTypesToCompress, isCompressionEnabled, isHttpAllowed, isHttpsAllowed, queryStringCachingBehavior, optimizationType, geoFilters, hostName, resourceState, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="origins" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt;" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="originHostHeader" Type="System.String" />
        <Parameter Name="originPath" Type="System.String" />
        <Parameter Name="contentTypesToCompress" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isCompressionEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isHttpAllowed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isHttpsAllowed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="queryStringCachingBehavior" Type="System.Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt;" />
        <Parameter Name="optimizationType" Type="System.String" />
        <Parameter Name="geoFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="resourceState" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="origins"><span data-ttu-id="83cb8-104">CDN によって提供されるコンテンツのソース。</span><span class="sxs-lookup"><span data-stu-id="83cb8-104">The source of the content being delivered via CDN.</span></span></param>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="originHostHeader"><span data-ttu-id="83cb8-105">CDN のホスト ヘッダーは、発生元へのコンテンツの要求と共に送信されます。</span><span class="sxs-lookup"><span data-stu-id="83cb8-105">The host header CDN sends along with content requests to origin.</span></span> <span data-ttu-id="83cb8-106">既定値は、元のホスト名です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-106">The default value is the host name of the origin.</span></span></param>
        <param name="originPath"><span data-ttu-id="83cb8-107">CDN が配信元に要求を送信するときに使用するパス。</span><span class="sxs-lookup"><span data-stu-id="83cb8-107">The path used when CDN sends request to origin.</span></span></param>
        <param name="contentTypesToCompress"><span data-ttu-id="83cb8-108">圧縮が適用されるコンテンツの種類の一覧です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-108">List of content types on which compression applies.</span></span> <span data-ttu-id="83cb8-109">値は、MIME の種類を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="83cb8-109">The value should be a valid MIME type.</span></span></param>
        <param name="isCompressionEnabled"><span data-ttu-id="83cb8-110">CDN のコンテンツの圧縮が有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-110">Indicates whether content compression is enabled on CDN.</span></span> <span data-ttu-id="83cb8-111">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-111">Default value is false.</span></span> <span data-ttu-id="83cb8-112">コンテンツとして提供の圧縮が有効になっている場合は、圧縮バージョンのユーザーを要求する場合に圧縮します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-112">If compression is enabled, content will be served as compressed if user requests for a compressed version.</span></span> <span data-ttu-id="83cb8-113">要求されたコンテンツが 1 バイト未満または 1 MB より大きい場合、コンテンツを CDN に圧縮されません。</span><span class="sxs-lookup"><span data-stu-id="83cb8-113">Content won't be compressed on CDN when requested content is smaller than 1 byte or larger than 1 MB.</span></span></param>
        <param name="isHttpAllowed"><span data-ttu-id="83cb8-114">HTTP トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-114">Indicates whether HTTP traffic is allowed on the endpoint.</span></span> <span data-ttu-id="83cb8-115">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-115">Default value is true.</span></span> <span data-ttu-id="83cb8-116">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="83cb8-116">At least one protocol (HTTP or HTTPS) must be allowed.</span></span></param>
        <param name="isHttpsAllowed"><span data-ttu-id="83cb8-117">HTTPS トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-117">Indicates whether HTTPS traffic is allowed on the endpoint.</span></span> <span data-ttu-id="83cb8-118">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-118">Default value is true.</span></span> <span data-ttu-id="83cb8-119">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="83cb8-119">At least one protocol (HTTP or HTTPS) must be allowed.</span></span></param>
        <param name="queryStringCachingBehavior"><span data-ttu-id="83cb8-120">クエリ文字列のキャッシュ動作を定義します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-120">Defines the query string caching behavior.</span></span> <span data-ttu-id="83cb8-121">使用可能な値が含まれます: 'IgnoreQueryString'、'BypassCaching'、'UseQueryString'、'NotSet'</span><span class="sxs-lookup"><span data-stu-id="83cb8-121">Possible values include: 'IgnoreQueryString', 'BypassCaching', 'UseQueryString', 'NotSet'</span></span></param>
        <param name="optimizationType"><span data-ttu-id="83cb8-122">顧客は、どのようなシナリオが欲しいこの CDN エンドポイントの最適化、ダウンロードなどに、Media services を指定できます。</span><span class="sxs-lookup"><span data-stu-id="83cb8-122">Customer can specify what scenario they want this CDN endpoint to optimize, e.g. Download, Media services.</span></span> <span data-ttu-id="83cb8-123">この情報を含むドリブンのシナリオの最適化を適用できます。</span><span class="sxs-lookup"><span data-stu-id="83cb8-123">With this information we can apply scenario driven optimization.</span></span></param>
        <param name="geoFilters"><span data-ttu-id="83cb8-124">CDN エンドポイント内のユーザー geo アクセスを定義する規則の一覧です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-124">List of rules defining user geo access within a CDN endpoint.</span></span> <span data-ttu-id="83cb8-125">各 geo フィルターは、指定されたパスまたはパス/pictures/のブロック APAC など、コンテンツにアクセス ルールを定義します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-125">Each geo filter defines an acess rule to a specified path or content, e.g. block APAC for path /pictures/</span></span></param>
        <param name="hostName"><span data-ttu-id="83cb8-126">エンドポイント {endpointname} として構造化のホスト名。{DNSZone} consoto.azureedge.net 例。</span><span class="sxs-lookup"><span data-stu-id="83cb8-126">The host name of the endpoint structured as {endpointName}.{DNSZone}, e.g. consoto.azureedge.net</span></span></param>
        <param name="resourceState"><span data-ttu-id="83cb8-127">エンドポイントのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="83cb8-127">Resource status of the endpoint.</span></span>
            <span data-ttu-id="83cb8-128">使用可能な値が含まれます: '作成中'、'削除'、' 実行中'、'から'、'停止'、'停止'</span><span class="sxs-lookup"><span data-stu-id="83cb8-128">Possible values include: 'Creating', 'Deleting', 'Running', 'Starting', 'Stopped', 'Stopping'</span></span></param>
        <param name="provisioningState"><span data-ttu-id="83cb8-129">エンドポイントの状態を準備しています。</span><span class="sxs-lookup"><span data-stu-id="83cb8-129">Provisioning status of the endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="83cb8-130">EndpointInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-130">Initializes a new instance of the EndpointInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentTypesToCompress">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContentTypesToCompress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContentTypesToCompress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.ContentTypesToCompress" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentTypesToCompress As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContentTypesToCompress : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.ContentTypesToCompress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contentTypesToCompress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-131">取得または圧縮が適用されるコンテンツの種類の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-131">Gets or sets list of content types on which compression applies.</span></span>
            <span data-ttu-id="83cb8-132">値は、MIME の種類を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="83cb8-132">The value should be a valid MIME type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.GeoFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoFilters As IList(Of GeoFilter)" />
      <MemberSignature Language="F#" Value="member this.GeoFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.GeoFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-133">取得または CDN エンドポイント内のユーザー geo アクセスを定義する規則の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-133">Gets or sets list of rules defining user geo access within a CDN endpoint.</span></span> <span data-ttu-id="83cb8-134">各 geo フィルターは、指定されたパスまたはパス/pictures/のブロック APAC など、コンテンツにアクセス ルールを定義します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-134">Each geo filter defines an acess rule to a specified path or content, e.g. block APAC for path /pictures/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-135">エンドポイント {endpointname} として構造化のホスト名を取得します。{DNSZone} consoto.azureedge.net 例。</span><span class="sxs-lookup"><span data-stu-id="83cb8-135">Gets the host name of the endpoint structured as {endpointName}.{DNSZone}, e.g. consoto.azureedge.net</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCompressionEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsCompressionEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsCompressionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.IsCompressionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsCompressionEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsCompressionEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.IsCompressionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isCompressionEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-136">取得または設定は、CDN のコンテンツの圧縮が有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-136">Gets or sets indicates whether content compression is enabled on CDN.</span></span> <span data-ttu-id="83cb8-137">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-137">Default value is false.</span></span> <span data-ttu-id="83cb8-138">コンテンツとして提供の圧縮が有効になっている場合は、圧縮バージョンのユーザーを要求する場合に圧縮します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-138">If compression is enabled, content will be served as compressed if user requests for a compressed version.</span></span> <span data-ttu-id="83cb8-139">要求されたコンテンツが 1 バイト未満または 1 MB より大きい場合、コンテンツを CDN に圧縮されません。</span><span class="sxs-lookup"><span data-stu-id="83cb8-139">Content won't be compressed on CDN when requested content is smaller than 1 byte or larger than 1 MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsHttpAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsHttpAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.IsHttpAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsHttpAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsHttpAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.IsHttpAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isHttpAllowed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-140">取得または設定は、HTTP トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-140">Gets or sets indicates whether HTTP traffic is allowed on the endpoint.</span></span> <span data-ttu-id="83cb8-141">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-141">Default value is true.</span></span> <span data-ttu-id="83cb8-142">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="83cb8-142">At least one protocol (HTTP or HTTPS) must be allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpsAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsHttpsAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsHttpsAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.IsHttpsAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsHttpsAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsHttpsAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.IsHttpsAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isHttpsAllowed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-143">取得または設定は、HTTPS トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-143">Gets or sets indicates whether HTTPS traffic is allowed on the endpoint.</span></span> <span data-ttu-id="83cb8-144">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-144">Default value is true.</span></span> <span data-ttu-id="83cb8-145">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="83cb8-145">At least one protocol (HTTP or HTTPS) must be allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizationType">
      <MemberSignature Language="C#" Value="public string OptimizationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OptimizationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.OptimizationType" />
      <MemberSignature Language="VB.NET" Value="Public Property OptimizationType As String" />
      <MemberSignature Language="F#" Value="member this.OptimizationType : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.OptimizationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.optimizationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-146">取得または設定顧客は、どのようなシナリオが欲しいこの CDN エンドポイントの最適化、ダウンロードなどに、Media services を指定できます。</span><span class="sxs-lookup"><span data-stu-id="83cb8-146">Gets or sets customer can specify what scenario they want this CDN endpoint to optimize, e.g. Download, Media services.</span></span> <span data-ttu-id="83cb8-147">この情報を含むドリブンのシナリオの最適化を適用できます。</span><span class="sxs-lookup"><span data-stu-id="83cb8-147">With this information we can apply scenario driven optimization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginHostHeader">
      <MemberSignature Language="C#" Value="public string OriginHostHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginHostHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.OriginHostHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginHostHeader As String" />
      <MemberSignature Language="F#" Value="member this.OriginHostHeader : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.OriginHostHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.originHostHeader")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-148">取得または CDN が配信元へのコンテンツの要求と共に送信ホスト ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-148">Gets or sets the host header CDN sends along with content requests to origin.</span></span> <span data-ttu-id="83cb8-149">既定値は、元のホスト名です。</span><span class="sxs-lookup"><span data-stu-id="83cb8-149">The default value is the host name of the origin.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginPath">
      <MemberSignature Language="C#" Value="public string OriginPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.OriginPath" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginPath As String" />
      <MemberSignature Language="F#" Value="member this.OriginPath : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.OriginPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.originPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-150">取得または CDN が配信元に要求を送信するときに使用するパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-150">Gets or sets the path used when CDN sends request to origin.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origins">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt; Origins { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt; Origins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.Origins" />
      <MemberSignature Language="VB.NET" Value="Public Property Origins As IList(Of DeepCreatedOrigin)" />
      <MemberSignature Language="F#" Value="member this.Origins : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.Origins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.origins")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-151">取得または CDN によって提供されるコンテンツのソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-151">Gets or sets the source of the content being delivered via CDN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
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
            <span data-ttu-id="83cb8-152">エンドポイントの状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-152">Gets provisioning status of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; QueryStringCachingBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; QueryStringCachingBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.QueryStringCachingBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryStringCachingBehavior As Nullable(Of QueryStringCachingBehavior)" />
      <MemberSignature Language="F#" Value="member this.QueryStringCachingBehavior : Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.QueryStringCachingBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.queryStringCachingBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-153">取得または設定は、クエリ文字列のキャッシュ動作を定義します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-153">Gets or sets defines the query string caching behavior.</span></span> <span data-ttu-id="83cb8-154">使用可能な値が含まれます: 'IgnoreQueryString'、'BypassCaching'、'UseQueryString'、'NotSet'</span><span class="sxs-lookup"><span data-stu-id="83cb8-154">Possible values include: 'IgnoreQueryString', 'BypassCaching', 'UseQueryString', 'NotSet'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.ResourceState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-155">エンドポイントのリソースの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-155">Gets resource status of the endpoint.</span></span> <span data-ttu-id="83cb8-156">使用可能な値が含まれます: '作成中'、'削除'、' 実行中'、'から'、'停止'、'停止'</span><span class="sxs-lookup"><span data-stu-id="83cb8-156">Possible values include: 'Creating', 'Deleting', 'Running', 'Starting', 'Stopped', 'Stopping'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="endpointInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83cb8-157">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="83cb8-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83cb8-158">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83cb8-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>