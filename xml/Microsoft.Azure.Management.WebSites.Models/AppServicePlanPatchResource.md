<Type Name="AppServicePlanPatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource">
  <TypeSignature Language="C#" Value="public class AppServicePlanPatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServicePlanPatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServicePlanPatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type AppServicePlanPatchResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="67ab9-101">App service プランの ARM リソースです。</span><span class="sxs-lookup"><span data-stu-id="67ab9-101">ARM resource for a app service plan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServicePlanPatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-102">AppServicePlanPatchResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-102">Initializes a new instance of the AppServicePlanPatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServicePlanPatchResource (string id = null, string name = null, string kind = null, string type = null, string appServicePlanPatchResourceName = null, string workerTierName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; status = null, string subscription = null, string adminSiteName = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, Nullable&lt;int&gt; maximumNumberOfWorkers = null, string geoRegion = null, Nullable&lt;bool&gt; perSiteScaling = null, Nullable&lt;int&gt; numberOfSites = null, Nullable&lt;bool&gt; isSpot = null, Nullable&lt;DateTime&gt; spotExpirationTime = null, string resourceGroup = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;int&gt; targetWorkerCount = null, Nullable&lt;int&gt; targetWorkerSizeId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string appServicePlanPatchResourceName, string workerTierName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; status, string subscription, string adminSiteName, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, valuetype System.Nullable`1&lt;int32&gt; maximumNumberOfWorkers, string geoRegion, valuetype System.Nullable`1&lt;bool&gt; perSiteScaling, valuetype System.Nullable`1&lt;int32&gt; numberOfSites, valuetype System.Nullable`1&lt;bool&gt; isSpot, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; spotExpirationTime, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;int32&gt; targetWorkerCount, valuetype System.Nullable`1&lt;int32&gt; targetWorkerSizeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.StatusOptions},System.String,System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource : string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; * string * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource (id, name, kind, type, appServicePlanPatchResourceName, workerTierName, status, subscription, adminSiteName, hostingEnvironmentProfile, maximumNumberOfWorkers, geoRegion, perSiteScaling, numberOfSites, isSpot, spotExpirationTime, resourceGroup, reserved, targetWorkerCount, targetWorkerSizeId, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="appServicePlanPatchResourceName" Type="System.String" />
        <Parameter Name="workerTierName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;" />
        <Parameter Name="subscription" Type="System.String" />
        <Parameter Name="adminSiteName" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="maximumNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="geoRegion" Type="System.String" />
        <Parameter Name="perSiteScaling" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="numberOfSites" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isSpot" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="spotExpirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetWorkerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetWorkerSizeId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="67ab9-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="67ab9-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="67ab9-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="67ab9-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="67ab9-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="67ab9-106">Resource type.</span></span></param>
        <param name="appServicePlanPatchResourceName"><span data-ttu-id="67ab9-107">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-107">Name for the App Service plan.</span></span></param>
        <param name="workerTierName"><span data-ttu-id="67ab9-108">App Service プランに割り当てられている対象となるワーカー層です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-108">Target worker tier assigned to the App Service plan.</span></span></param>
        <param name="status"><span data-ttu-id="67ab9-109">App Service プランの状態です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-109">App Service plan status.</span></span> <span data-ttu-id="67ab9-110">使用可能な値が含まれます: '準備完了'、'保留中'、'作成'</span><span class="sxs-lookup"><span data-stu-id="67ab9-110">Possible values include: 'Ready', 'Pending', 'Creating'</span></span></param>
        <param name="subscription"><span data-ttu-id="67ab9-111">App Service プランのサブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="67ab9-111">App Service plan subscription.</span></span></param>
        <param name="adminSiteName"><span data-ttu-id="67ab9-112">App Service プランの管理のサイトです。</span><span class="sxs-lookup"><span data-stu-id="67ab9-112">App Service plan administration site.</span></span></param>
        <param name="hostingEnvironmentProfile"><span data-ttu-id="67ab9-113">App Service プランに使用する App Service 環境を指定します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-113">Specification for the App Service Environment to use for the App Service plan.</span></span></param>
        <param name="maximumNumberOfWorkers"><span data-ttu-id="67ab9-114">この App Service プランに割り当てることのできるインスタンスの最大数。</span><span class="sxs-lookup"><span data-stu-id="67ab9-114">Maximum number of instances that can be assigned to this App Service plan.</span></span></param>
        <param name="geoRegion"><span data-ttu-id="67ab9-115">App Service プランの地理的な場所です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-115">Geographical location for the App Service plan.</span></span></param>
        <param name="perSiteScaling"><span data-ttu-id="67ab9-116">場合&lt;コード&gt;true&lt;/code&gt;アプリがこの App Service プランに割り当てられている個別に拡張することができます。</span><span class="sxs-lookup"><span data-stu-id="67ab9-116">If &lt;code&gt;true&lt;/code&gt;, apps assigned to this App Service plan can be scaled independently.</span></span>
            <span data-ttu-id="67ab9-117">場合&lt;コード&gt;false&lt;/code&gt;プランのすべてのインスタンスにこの App Service プランに割り当てられているアプリをスケールします。</span><span class="sxs-lookup"><span data-stu-id="67ab9-117">If &lt;code&gt;false&lt;/code&gt;, apps assigned to this App Service plan will scale to all instances of the plan.</span></span></param>
        <param name="numberOfSites"><span data-ttu-id="67ab9-118">この App Service プランに割り当てられているアプリの数です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-118">Number of apps assigned to this App Service plan.</span></span></param>
        <param name="isSpot"><span data-ttu-id="67ab9-119">場合&lt;コード&gt;true&lt;/code&gt;、スポット インスタンスこの App Service プランを所有します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-119">If &lt;code&gt;true&lt;/code&gt;, this App Service Plan owns spot instances.</span></span></param>
        <param name="spotExpirationTime"><span data-ttu-id="67ab9-120">サーバー ファームの有効期限が切れる時刻。</span><span class="sxs-lookup"><span data-stu-id="67ab9-120">The time when the server farm expires.</span></span> <span data-ttu-id="67ab9-121">スポット サーバー ファームの場合にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-121">Valid only if it is a spot server farm.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="67ab9-122">App Service プランのリソース グループです。</span><span class="sxs-lookup"><span data-stu-id="67ab9-122">Resource group of the App Service plan.</span></span></param>
        <param name="reserved"><span data-ttu-id="67ab9-123">予約済み。</span><span class="sxs-lookup"><span data-stu-id="67ab9-123">Reserved.</span></span></param>
        <param name="targetWorkerCount"><span data-ttu-id="67ab9-124">ワーカーの数をスケーリングします。</span><span class="sxs-lookup"><span data-stu-id="67ab9-124">Scaling worker count.</span></span></param>
        <param name="targetWorkerSizeId"><span data-ttu-id="67ab9-125">スケーリングのワーカー サイズ id。</span><span class="sxs-lookup"><span data-stu-id="67ab9-125">Scaling worker size ID.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="67ab9-126">App Service 環境の状態を準備しています。</span><span class="sxs-lookup"><span data-stu-id="67ab9-126">Provisioning state of the App Service Environment.</span></span> <span data-ttu-id="67ab9-127">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="67ab9-127">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span></param>
        <summary>
            <span data-ttu-id="67ab9-128">AppServicePlanPatchResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-128">Initializes a new instance of the AppServicePlanPatchResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminSiteName">
      <MemberSignature Language="C#" Value="public string AdminSiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminSiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AdminSiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminSiteName As String" />
      <MemberSignature Language="F#" Value="member this.AdminSiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AdminSiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adminSiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-129">取得またはアプリ サービス プランの管理サイトを設定します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-129">Gets or sets app Service plan administration site.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlanPatchResourceName">
      <MemberSignature Language="C#" Value="public string AppServicePlanPatchResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlanPatchResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AppServicePlanPatchResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServicePlanPatchResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlanPatchResourceName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.AppServicePlanPatchResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-130">取得または App Service プランの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-130">Gets or sets name for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoRegion">
      <MemberSignature Language="C#" Value="public string GeoRegion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GeoRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.GeoRegion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoRegion As String" />
      <MemberSignature Language="F#" Value="member this.GeoRegion : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.GeoRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-131">App Service プランの地理的な場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-131">Gets geographical location for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-132">取得または、App Service 環境の App Service プランに使用するための仕様を設定します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-132">Gets or sets specification for the App Service Environment to use for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSpot">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSpot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSpot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.IsSpot" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSpot As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSpot : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.IsSpot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isSpot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-133">場合取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt;、スポット インスタンスこの App Service プランを所有しています。</span><span class="sxs-lookup"><span data-stu-id="67ab9-133">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, this App Service Plan owns spot instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.MaximumNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.MaximumNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumNumberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-134">この App Service プランに割り当てることのできるインスタンスの最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-134">Gets maximum number of instances that can be assigned to this App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfSites">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfSites { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfSites" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.NumberOfSites" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfSites As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfSites : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.NumberOfSites" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfSites")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-135">この App Service プランに割り当てられているアプリの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-135">Gets number of apps assigned to this App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerSiteScaling">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PerSiteScaling { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PerSiteScaling" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.PerSiteScaling" />
      <MemberSignature Language="VB.NET" Value="Public Property PerSiteScaling As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PerSiteScaling : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.PerSiteScaling" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.perSiteScaling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-136">場合取得または設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt 以外の場合は、この App Service プランに割り当てられているアプリ個別に拡張することができます。</span><span class="sxs-lookup"><span data-stu-id="67ab9-136">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, apps assigned to this App Service plan can be scaled independently.</span></span>
            <span data-ttu-id="67ab9-137">場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;、プランのすべてのインスタンスにこの App Service プランに割り当てられているアプリをスケールします。</span><span class="sxs-lookup"><span data-stu-id="67ab9-137">If &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;, apps assigned to this App Service plan will scale to all instances of the plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-138">App Service 環境の状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-138">Gets provisioning state of the App Service Environment.</span></span> <span data-ttu-id="67ab9-139">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="67ab9-139">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reserved")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-140">取得または予約済みに設定します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-140">Gets or sets reserved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-141">App Service プランのリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-141">Gets resource group of the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SpotExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SpotExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SpotExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.SpotExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SpotExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SpotExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.SpotExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.spotExpirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-142">取得またはサーバー ファームの有効期限が切れる時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-142">Gets or sets the time when the server farm expires.</span></span> <span data-ttu-id="67ab9-143">スポット サーバー ファームの場合にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="67ab9-143">Valid only if it is a spot server farm.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of StatusOptions)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-144">アプリ サービス プランの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-144">Gets app Service plan status.</span></span> <span data-ttu-id="67ab9-145">使用可能な値が含まれます: '準備完了'、'保留中'、'作成'</span><span class="sxs-lookup"><span data-stu-id="67ab9-145">Possible values include: 'Ready', 'Pending', 'Creating'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscription">
      <MemberSignature Language="C#" Value="public string Subscription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subscription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Subscription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscription As String" />
      <MemberSignature Language="F#" Value="member this.Subscription : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.Subscription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-146">アプリ サービス プランのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-146">Gets app Service plan subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetWorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetWorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetWorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetWorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetWorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetWorkerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-147">取得または設定のワーカーの数をスケーリングします。</span><span class="sxs-lookup"><span data-stu-id="67ab9-147">Gets or sets scaling worker count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetWorkerSizeId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetWorkerSizeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetWorkerSizeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerSizeId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetWorkerSizeId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetWorkerSizeId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.TargetWorkerSizeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetWorkerSizeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-148">取得または設定スケーリング ワーカー サイズ id。</span><span class="sxs-lookup"><span data-stu-id="67ab9-148">Gets or sets scaling worker size ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerTierName">
      <MemberSignature Language="C#" Value="public string WorkerTierName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerTierName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.WorkerTierName" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerTierName As String" />
      <MemberSignature Language="F#" Value="member this.WorkerTierName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource.WorkerTierName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerTierName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67ab9-149">取得または App Service プランに割り当てられている対象となるワーカー層を設定します。</span><span class="sxs-lookup"><span data-stu-id="67ab9-149">Gets or sets target worker tier assigned to the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>