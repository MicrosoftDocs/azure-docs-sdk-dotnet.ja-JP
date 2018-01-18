<Type Name="EndpointUpdateParametersInner" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner">
  <TypeSignature Language="C#" Value="public class EndpointUpdateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EndpointUpdateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class EndpointUpdateParametersInner" />
  <TypeSignature Language="F#" Value="type EndpointUpdateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="db7b9-101">新しいエンドポイントの作成に必要なプロパティです。</span><span class="sxs-lookup"><span data-stu-id="db7b9-101">Properties required to create a new endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointUpdateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="db7b9-102">EndpointUpdateParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-102">Initializes a new instance of the EndpointUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EndpointUpdateParametersInner (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string originHostHeader = null, string originPath = null, System.Collections.Generic.IList&lt;string&gt; contentTypesToCompress = null, Nullable&lt;bool&gt; isCompressionEnabled = null, Nullable&lt;bool&gt; isHttpAllowed = null, Nullable&lt;bool&gt; isHttpsAllowed = null, Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; queryStringCachingBehavior = null, string optimizationType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string originHostHeader, string originPath, class System.Collections.Generic.IList`1&lt;string&gt; contentTypesToCompress, valuetype System.Nullable`1&lt;bool&gt; isCompressionEnabled, valuetype System.Nullable`1&lt;bool&gt; isHttpAllowed, valuetype System.Nullable`1&lt;bool&gt; isHttpsAllowed, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; queryStringCachingBehavior, string optimizationType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional originHostHeader As String = null, Optional originPath As String = null, Optional contentTypesToCompress As IList(Of String) = null, Optional isCompressionEnabled As Nullable(Of Boolean) = null, Optional isHttpAllowed As Nullable(Of Boolean) = null, Optional isHttpsAllowed As Nullable(Of Boolean) = null, Optional queryStringCachingBehavior As Nullable(Of QueryStringCachingBehavior) = null, Optional optimizationType As String = null, Optional geoFilters As IList(Of GeoFilter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner : System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner (tags, originHostHeader, originPath, contentTypesToCompress, isCompressionEnabled, isHttpAllowed, isHttpsAllowed, queryStringCachingBehavior, optimizationType, geoFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
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
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="db7b9-103">エンドポイントのタグ。</span><span class="sxs-lookup"><span data-stu-id="db7b9-103">Endpoint tags.</span></span></param>
        <param name="originHostHeader"><span data-ttu-id="db7b9-104">CDN のホスト ヘッダーは、発生元へのコンテンツの要求と共に送信されます。</span><span class="sxs-lookup"><span data-stu-id="db7b9-104">The host header CDN sends along with content requests to origin.</span></span> <span data-ttu-id="db7b9-105">既定値は、元のホスト名です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-105">The default value is the host name of the origin.</span></span></param>
        <param name="originPath"><span data-ttu-id="db7b9-106">CDN が配信元に要求を送信するときに使用するパス。</span><span class="sxs-lookup"><span data-stu-id="db7b9-106">The path used when CDN sends request to origin.</span></span></param>
        <param name="contentTypesToCompress"><span data-ttu-id="db7b9-107">圧縮が適用されるコンテンツの種類の一覧です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-107">List of content types on which compression applies.</span></span> <span data-ttu-id="db7b9-108">値は、MIME の種類を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="db7b9-108">The value should be a valid MIME type.</span></span></param>
        <param name="isCompressionEnabled"><span data-ttu-id="db7b9-109">CDN のコンテンツの圧縮が有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-109">Indicates whether content compression is enabled on CDN.</span></span> <span data-ttu-id="db7b9-110">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-110">Default value is false.</span></span> <span data-ttu-id="db7b9-111">コンテンツとして提供の圧縮が有効になっている場合は、圧縮バージョンのユーザーを要求する場合に圧縮します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-111">If compression is enabled, content will be served as compressed if user requests for a compressed version.</span></span> <span data-ttu-id="db7b9-112">要求されたコンテンツが 1 バイト未満または 1 MB より大きい場合、コンテンツを CDN に圧縮されません。</span><span class="sxs-lookup"><span data-stu-id="db7b9-112">Content won't be compressed on CDN when requested content is smaller than 1 byte or larger than 1 MB.</span></span></param>
        <param name="isHttpAllowed"><span data-ttu-id="db7b9-113">HTTP トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-113">Indicates whether HTTP traffic is allowed on the endpoint.</span></span> <span data-ttu-id="db7b9-114">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-114">Default value is true.</span></span> <span data-ttu-id="db7b9-115">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="db7b9-115">At least one protocol (HTTP or HTTPS) must be allowed.</span></span></param>
        <param name="isHttpsAllowed"><span data-ttu-id="db7b9-116">HTTPS トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-116">Indicates whether HTTPS traffic is allowed on the endpoint.</span></span> <span data-ttu-id="db7b9-117">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-117">Default value is true.</span></span> <span data-ttu-id="db7b9-118">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="db7b9-118">At least one protocol (HTTP or HTTPS) must be allowed.</span></span></param>
        <param name="queryStringCachingBehavior"><span data-ttu-id="db7b9-119">クエリ文字列のキャッシュ動作を定義します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-119">Defines the query string caching behavior.</span></span> <span data-ttu-id="db7b9-120">使用可能な値が含まれます: 'IgnoreQueryString'、'BypassCaching'、'UseQueryString'、'NotSet'</span><span class="sxs-lookup"><span data-stu-id="db7b9-120">Possible values include: 'IgnoreQueryString', 'BypassCaching', 'UseQueryString', 'NotSet'</span></span></param>
        <param name="optimizationType"><span data-ttu-id="db7b9-121">顧客は、どのようなシナリオが欲しいこの CDN エンドポイントの最適化、ダウンロードなどに、Media services を指定できます。</span><span class="sxs-lookup"><span data-stu-id="db7b9-121">Customer can specify what scenario they want this CDN endpoint to optimize, e.g. Download, Media services.</span></span> <span data-ttu-id="db7b9-122">この情報を含むドリブンのシナリオの最適化を適用できます。</span><span class="sxs-lookup"><span data-stu-id="db7b9-122">With this information we can apply scenario driven optimization.</span></span></param>
        <param name="geoFilters"><span data-ttu-id="db7b9-123">CDN エンドポイント内のユーザー geo アクセスを定義する規則の一覧です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-123">List of rules defining user geo access within a CDN endpoint.</span></span> <span data-ttu-id="db7b9-124">各 geo フィルターは、指定されたパスまたはパス/pictures/のブロック APAC など、コンテンツにアクセス ルールを定義します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-124">Each geo filter defines an acess rule to a specified path or content, e.g. block APAC for path /pictures/</span></span></param>
        <summary>
            <span data-ttu-id="db7b9-125">EndpointUpdateParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-125">Initializes a new instance of the EndpointUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentTypesToCompress">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContentTypesToCompress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContentTypesToCompress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.ContentTypesToCompress" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentTypesToCompress As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContentTypesToCompress : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.ContentTypesToCompress" />
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
            <span data-ttu-id="db7b9-126">取得または圧縮が適用されるコンテンツの種類の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-126">Gets or sets list of content types on which compression applies.</span></span>
            <span data-ttu-id="db7b9-127">値は、MIME の種類を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="db7b9-127">The value should be a valid MIME type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.GeoFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoFilters As IList(Of GeoFilter)" />
      <MemberSignature Language="F#" Value="member this.GeoFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.GeoFilters" />
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
            <span data-ttu-id="db7b9-128">取得または CDN エンドポイント内のユーザー geo アクセスを定義する規則の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-128">Gets or sets list of rules defining user geo access within a CDN endpoint.</span></span> <span data-ttu-id="db7b9-129">各 geo フィルターは、指定されたパスまたはパス/pictures/のブロック APAC など、コンテンツにアクセス ルールを定義します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-129">Each geo filter defines an acess rule to a specified path or content, e.g. block APAC for path /pictures/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCompressionEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsCompressionEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsCompressionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsCompressionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsCompressionEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsCompressionEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsCompressionEnabled" />
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
            <span data-ttu-id="db7b9-130">取得または設定は、CDN のコンテンツの圧縮が有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-130">Gets or sets indicates whether content compression is enabled on CDN.</span></span> <span data-ttu-id="db7b9-131">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-131">Default value is false.</span></span> <span data-ttu-id="db7b9-132">コンテンツとして提供の圧縮が有効になっている場合は、圧縮バージョンのユーザーを要求する場合に圧縮します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-132">If compression is enabled, content will be served as compressed if user requests for a compressed version.</span></span> <span data-ttu-id="db7b9-133">要求されたコンテンツが 1 バイト未満または 1 MB より大きい場合、コンテンツを CDN に圧縮されません。</span><span class="sxs-lookup"><span data-stu-id="db7b9-133">Content won't be compressed on CDN when requested content is smaller than 1 byte or larger than 1 MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsHttpAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsHttpAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsHttpAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsHttpAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpAllowed" />
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
            <span data-ttu-id="db7b9-134">取得または設定は、HTTP トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-134">Gets or sets indicates whether HTTP traffic is allowed on the endpoint.</span></span> <span data-ttu-id="db7b9-135">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-135">Default value is true.</span></span> <span data-ttu-id="db7b9-136">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="db7b9-136">At least one protocol (HTTP or HTTPS) must be allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpsAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsHttpsAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsHttpsAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpsAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsHttpsAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsHttpsAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.IsHttpsAllowed" />
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
            <span data-ttu-id="db7b9-137">取得または設定は、HTTPS トラフィックが、エンドポイントで許可されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-137">Gets or sets indicates whether HTTPS traffic is allowed on the endpoint.</span></span> <span data-ttu-id="db7b9-138">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-138">Default value is true.</span></span> <span data-ttu-id="db7b9-139">少なくとも 1 つのプロトコル (HTTP または HTTPS) を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="db7b9-139">At least one protocol (HTTP or HTTPS) must be allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizationType">
      <MemberSignature Language="C#" Value="public string OptimizationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OptimizationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OptimizationType" />
      <MemberSignature Language="VB.NET" Value="Public Property OptimizationType As String" />
      <MemberSignature Language="F#" Value="member this.OptimizationType : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OptimizationType" />
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
            <span data-ttu-id="db7b9-140">取得または設定顧客は、どのようなシナリオが欲しいこの CDN エンドポイントの最適化、ダウンロードなどに、Media services を指定できます。</span><span class="sxs-lookup"><span data-stu-id="db7b9-140">Gets or sets customer can specify what scenario they want this CDN endpoint to optimize, e.g. Download, Media services.</span></span> <span data-ttu-id="db7b9-141">この情報を含むドリブンのシナリオの最適化を適用できます。</span><span class="sxs-lookup"><span data-stu-id="db7b9-141">With this information we can apply scenario driven optimization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginHostHeader">
      <MemberSignature Language="C#" Value="public string OriginHostHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginHostHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginHostHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginHostHeader As String" />
      <MemberSignature Language="F#" Value="member this.OriginHostHeader : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginHostHeader" />
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
            <span data-ttu-id="db7b9-142">取得または CDN が配信元へのコンテンツの要求と共に送信ホスト ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-142">Gets or sets the host header CDN sends along with content requests to origin.</span></span> <span data-ttu-id="db7b9-143">既定値は、元のホスト名です。</span><span class="sxs-lookup"><span data-stu-id="db7b9-143">The default value is the host name of the origin.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginPath">
      <MemberSignature Language="C#" Value="public string OriginPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginPath" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginPath As String" />
      <MemberSignature Language="F#" Value="member this.OriginPath : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.OriginPath" />
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
            <span data-ttu-id="db7b9-144">取得または CDN が配信元に要求を送信するときに使用するパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-144">Gets or sets the path used when CDN sends request to origin.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; QueryStringCachingBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; QueryStringCachingBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.QueryStringCachingBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryStringCachingBehavior As Nullable(Of QueryStringCachingBehavior)" />
      <MemberSignature Language="F#" Value="member this.QueryStringCachingBehavior : Nullable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.QueryStringCachingBehavior" />
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
            <span data-ttu-id="db7b9-145">取得または設定は、クエリ文字列のキャッシュ動作を定義します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-145">Gets or sets defines the query string caching behavior.</span></span> <span data-ttu-id="db7b9-146">使用可能な値が含まれます: 'IgnoreQueryString'、'BypassCaching'、'UseQueryString'、'NotSet'</span><span class="sxs-lookup"><span data-stu-id="db7b9-146">Possible values include: 'IgnoreQueryString', 'BypassCaching', 'UseQueryString', 'NotSet'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointUpdateParametersInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="db7b9-147">取得またはエンドポイント タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="db7b9-147">Gets or sets endpoint tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>