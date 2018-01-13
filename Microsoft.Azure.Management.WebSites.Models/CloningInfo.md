<Type Name="CloningInfo" FullName="Microsoft.Azure.Management.WebSites.Models.CloningInfo">
  <TypeSignature Language="C#" Value="public class CloningInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloningInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CloningInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class CloningInfo" />
  <TypeSignature Language="F#" Value="type CloningInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="666d9-101">複製操作に必要な情報です。</span><span class="sxs-lookup"><span data-stu-id="666d9-101">Information needed for cloning operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloningInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CloningInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="666d9-102">CloningInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="666d9-102">Initializes a new instance of the CloningInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloningInfo (string sourceWebAppId, Nullable&lt;Guid&gt; correlationId = null, Nullable&lt;bool&gt; overwrite = null, Nullable&lt;bool&gt; cloneCustomHostNames = null, Nullable&lt;bool&gt; cloneSourceControl = null, string hostingEnvironment = null, System.Collections.Generic.IDictionary&lt;string,string&gt; appSettingsOverrides = null, Nullable&lt;bool&gt; configureLoadBalancing = null, string trafficManagerProfileId = null, string trafficManagerProfileName = null, Nullable&lt;bool&gt; ignoreQuotas = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceWebAppId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; correlationId, valuetype System.Nullable`1&lt;bool&gt; overwrite, valuetype System.Nullable`1&lt;bool&gt; cloneCustomHostNames, valuetype System.Nullable`1&lt;bool&gt; cloneSourceControl, string hostingEnvironment, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; appSettingsOverrides, valuetype System.Nullable`1&lt;bool&gt; configureLoadBalancing, string trafficManagerProfileId, string trafficManagerProfileName, valuetype System.Nullable`1&lt;bool&gt; ignoreQuotas) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CloningInfo.#ctor(System.String,System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceWebAppId As String, Optional correlationId As Nullable(Of Guid) = null, Optional overwrite As Nullable(Of Boolean) = null, Optional cloneCustomHostNames As Nullable(Of Boolean) = null, Optional cloneSourceControl As Nullable(Of Boolean) = null, Optional hostingEnvironment As String = null, Optional appSettingsOverrides As IDictionary(Of String, String) = null, Optional configureLoadBalancing As Nullable(Of Boolean) = null, Optional trafficManagerProfileId As String = null, Optional trafficManagerProfileName As String = null, Optional ignoreQuotas As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CloningInfo : string * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.CloningInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.CloningInfo (sourceWebAppId, correlationId, overwrite, cloneCustomHostNames, cloneSourceControl, hostingEnvironment, appSettingsOverrides, configureLoadBalancing, trafficManagerProfileId, trafficManagerProfileName, ignoreQuotas)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceWebAppId" Type="System.String" />
        <Parameter Name="correlationId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cloneCustomHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cloneSourceControl" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
        <Parameter Name="appSettingsOverrides" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="configureLoadBalancing" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="trafficManagerProfileId" Type="System.String" />
        <Parameter Name="trafficManagerProfileName" Type="System.String" />
        <Parameter Name="ignoreQuotas" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sourceWebAppId"><span data-ttu-id="666d9-103">ソースのアプリの ARM リソース ID です。</span><span class="sxs-lookup"><span data-stu-id="666d9-103">ARM resource ID of the source app.</span></span> <span data-ttu-id="666d9-104">アプリのリソース ID はフォーム/subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName} 運用スロットと/subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} の他のスロット。</span><span class="sxs-lookup"><span data-stu-id="666d9-104">App resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName} for production slots and /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} for other slots.</span></span></param>
        <param name="correlationId"><span data-ttu-id="666d9-105">複製操作の相関 ID です。</span><span class="sxs-lookup"><span data-stu-id="666d9-105">Correlation ID of cloning operation.</span></span>
            <span data-ttu-id="666d9-106">この ID は、同じスナップショットを使用するには、同時に複数の複製操作を関連付けます。</span><span class="sxs-lookup"><span data-stu-id="666d9-106">This ID ties multiple cloning operations together to use the same snapshot.</span></span></param>
        <param name="overwrite"><span data-ttu-id="666d9-107">&lt;コード&gt;true&lt;/code&gt;先アプリ; を上書きするそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="666d9-107">&lt;code&gt;true&lt;/code&gt; to overwrite destination app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="cloneCustomHostNames"><span data-ttu-id="666d9-108">&lt;コード&gt;true&lt;/code&gt;ソース アプリ; からのカスタム ホスト名を複製するそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="666d9-108">&lt;code&gt;true&lt;/code&gt; to clone custom hostnames from source app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="cloneSourceControl"><span data-ttu-id="666d9-109">&lt;コード&gt;true&lt;/code&gt;ソース アプリ; からのソース管理を複製するそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="666d9-109">&lt;code&gt;true&lt;/code&gt; to clone source control from source app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="hostingEnvironment"><span data-ttu-id="666d9-110">App Service 環境。</span><span class="sxs-lookup"><span data-stu-id="666d9-110">App Service Environment.</span></span></param>
        <param name="appSettingsOverrides"><span data-ttu-id="666d9-111">クローンとして作成されたアプリのアプリケーション設定をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="666d9-111">Application setting overrides for cloned app.</span></span> <span data-ttu-id="666d9-112">指定した場合、これらの設定はソース アプリから複製された設定をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="666d9-112">If specified, these settings override the settings cloned from source app.</span></span> <span data-ttu-id="666d9-113">それ以外の場合、アプリのソースからのアプリケーションの設定が保持されます。</span><span class="sxs-lookup"><span data-stu-id="666d9-113">Otherwise, application settings from source app are retained.</span></span></param>
        <param name="configureLoadBalancing"><span data-ttu-id="666d9-114">&lt;コード&gt;true&lt;/code&gt;元とコピー先のアプリケーションの負荷分散を構成します。</span><span class="sxs-lookup"><span data-stu-id="666d9-114">&lt;code&gt;true&lt;/code&gt; to configure load balancing for source and destination app.</span></span></param>
        <param name="trafficManagerProfileId"><span data-ttu-id="666d9-115">ARM のリソース ID、Traffic Manager プロファイルが存在する場合は、使用します。</span><span class="sxs-lookup"><span data-stu-id="666d9-115">ARM resource ID of the Traffic Manager profile to use, if it exists.</span></span> <span data-ttu-id="666d9-116">Traffic Manager のリソース ID はフォーム/subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName の} です。</span><span class="sxs-lookup"><span data-stu-id="666d9-116">Traffic Manager resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.</span></span></param>
        <param name="trafficManagerProfileName"><span data-ttu-id="666d9-117">作成する Traffic Manager プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="666d9-117">Name of Traffic Manager profile to create.</span></span> <span data-ttu-id="666d9-118">Traffic Manager プロファイルが既に存在しない場合のみ必要です。</span><span class="sxs-lookup"><span data-stu-id="666d9-118">This is only needed if Traffic Manager profile does not already exist.</span></span></param>
        <param name="ignoreQuotas"><span data-ttu-id="666d9-119">&lt;コード&gt;true&lt;/code&gt;無視されます。 それ以外の場合、クォータがある場合&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="666d9-119">&lt;code&gt;true&lt;/code&gt; if quotas should be ignored; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <summary>
            <span data-ttu-id="666d9-120">CloningInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="666d9-120">Initializes a new instance of the CloningInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppSettingsOverrides">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; AppSettingsOverrides { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; AppSettingsOverrides" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.AppSettingsOverrides" />
      <MemberSignature Language="VB.NET" Value="Public Property AppSettingsOverrides As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.AppSettingsOverrides : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.AppSettingsOverrides" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appSettingsOverrides")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-121">取得またはクローンとして作成されたアプリのアプリケーション設定の上書きを設定します。</span><span class="sxs-lookup"><span data-stu-id="666d9-121">Gets or sets application setting overrides for cloned app.</span></span> <span data-ttu-id="666d9-122">指定した場合、これらの設定はソース アプリから複製された設定をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="666d9-122">If specified, these settings override the settings cloned from source app.</span></span> <span data-ttu-id="666d9-123">それ以外の場合、アプリのソースからのアプリケーションの設定が保持されます。</span><span class="sxs-lookup"><span data-stu-id="666d9-123">Otherwise, application settings from source app are retained.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneCustomHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CloneCustomHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CloneCustomHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneCustomHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property CloneCustomHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CloneCustomHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneCustomHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloneCustomHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-124">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; 元のアプリからのカスタム ホスト名を複製するそれ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp; 。gt;。</span><span class="sxs-lookup"><span data-stu-id="666d9-124">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to clone custom hostnames from source app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneSourceControl">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CloneSourceControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CloneSourceControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CloneSourceControl As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CloneSourceControl : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.CloneSourceControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloneSourceControl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-125">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; 元のアプリからソース管理のクローンを作成する場合は、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt。;.</span><span class="sxs-lookup"><span data-stu-id="666d9-125">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to clone source control from source app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigureLoadBalancing">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ConfigureLoadBalancing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ConfigureLoadBalancing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.ConfigureLoadBalancing" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigureLoadBalancing As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ConfigureLoadBalancing : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.ConfigureLoadBalancing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="configureLoadBalancing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-126">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; 元とコピー先のアプリケーションの負荷分散を構成します。</span><span class="sxs-lookup"><span data-stu-id="666d9-126">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to configure load balancing for source and destination app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="correlationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-127">取得または複製操作の相関 ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="666d9-127">Gets or sets correlation ID of cloning operation.</span></span> <span data-ttu-id="666d9-128">この ID は、同じスナップショットを使用するには、同時に複数の複製操作を関連付けます。</span><span class="sxs-lookup"><span data-stu-id="666d9-128">This ID ties multiple cloning operations together to use the same snapshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-129">取得または app Service 環境を設定します。</span><span class="sxs-lookup"><span data-stu-id="666d9-129">Gets or sets app Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreQuotas">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.IgnoreQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreQuotas As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreQuotas : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.IgnoreQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-130">取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; 無視されます。 それ以外の場合、クォータがある場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="666d9-130">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if quotas should be ignored; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-131">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 対象のアプリ; を上書きするそれ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="666d9-131">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to overwrite destination app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceWebAppId">
      <MemberSignature Language="C#" Value="public string SourceWebAppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceWebAppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.SourceWebAppId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceWebAppId As String" />
      <MemberSignature Language="F#" Value="member this.SourceWebAppId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.SourceWebAppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceWebAppId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-132">取得またはソース アプリの ARM リソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="666d9-132">Gets or sets ARM resource ID of the source app.</span></span> <span data-ttu-id="666d9-133">アプリのリソース ID はフォーム/subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName} 運用スロットと/subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} の他のスロット。</span><span class="sxs-lookup"><span data-stu-id="666d9-133">App resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName} for production slots and /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Web/sites/{siteName}/slots/{slotName} for other slots.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerProfileId">
      <MemberSignature Language="C#" Value="public string TrafficManagerProfileId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficManagerProfileId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileId" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficManagerProfileId As String" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerProfileId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="trafficManagerProfileId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-134">取得または存在する場合に使用するには、Traffic Manager プロファイルの ARM リソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="666d9-134">Gets or sets ARM resource ID of the Traffic Manager profile to use, if it exists.</span></span> <span data-ttu-id="666d9-135">Traffic Manager のリソース ID はフォーム/subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName の} です。</span><span class="sxs-lookup"><span data-stu-id="666d9-135">Traffic Manager resource ID is of the form /subscriptions/{subId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles/{profileName}.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerProfileName">
      <MemberSignature Language="C#" Value="public string TrafficManagerProfileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficManagerProfileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficManagerProfileName As String" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerProfileName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CloningInfo.TrafficManagerProfileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="trafficManagerProfileName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="666d9-136">取得または作成する Traffic Manager プロファイルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="666d9-136">Gets or sets name of Traffic Manager profile to create.</span></span> <span data-ttu-id="666d9-137">Traffic Manager プロファイルが既に存在しない場合のみ必要です。</span><span class="sxs-lookup"><span data-stu-id="666d9-137">This is only needed if Traffic Manager profile does not already exist.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CloningInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloningInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="666d9-138">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="666d9-138">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="666d9-139">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="666d9-139">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>