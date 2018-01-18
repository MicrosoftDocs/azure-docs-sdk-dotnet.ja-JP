<Type Name="Usage" FullName="Microsoft.Azure.Management.WebSites.Models.Usage">
  <TypeSignature Language="C#" Value="public class Usage : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Usage extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Usage" />
  <TypeSignature Language="VB.NET" Value="Public Class Usage&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type Usage = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="95de7-101">クォータ リソースの使用量。</span><span class="sxs-lookup"><span data-stu-id="95de7-101">Usage of the quota resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Usage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="95de7-102">使用状況のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="95de7-102">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage (string id = null, string name = null, string kind = null, string type = null, string displayName = null, string usageName = null, string resourceName = null, string unit = null, Nullable&lt;long&gt; currentValue = null, Nullable&lt;long&gt; limit = null, Nullable&lt;DateTime&gt; nextResetTime = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode = null, string siteMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string displayName, string usageName, string resourceName, string unit, valuetype System.Nullable`1&lt;int64&gt; currentValue, valuetype System.Nullable`1&lt;int64&gt; limit, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextResetTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; computeMode, string siteMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Usage.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional displayName As String = null, Optional usageName As String = null, Optional resourceName As String = null, Optional unit As String = null, Optional currentValue As Nullable(Of Long) = null, Optional limit As Nullable(Of Long) = null, Optional nextResetTime As Nullable(Of DateTime) = null, Optional computeMode As Nullable(Of ComputeModeOptions) = null, Optional siteMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Usage : string * string * string * string * string * string * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.Usage" Usage="new Microsoft.Azure.Management.WebSites.Models.Usage (id, name, kind, type, displayName, usageName, resourceName, unit, currentValue, limit, nextResetTime, computeMode, siteMode)" />
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
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="usageName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="nextResetTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="computeMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;" />
        <Parameter Name="siteMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="95de7-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="95de7-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="95de7-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="95de7-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="95de7-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="95de7-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="95de7-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="95de7-106">Resource type.</span></span></param>
        <param name="displayName"><span data-ttu-id="95de7-107">UI に表示されるフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="95de7-107">Friendly name shown in the UI.</span></span></param>
        <param name="usageName"><span data-ttu-id="95de7-108">クォータの名前です。</span><span class="sxs-lookup"><span data-stu-id="95de7-108">Name of the quota.</span></span></param>
        <param name="resourceName"><span data-ttu-id="95de7-109">クォータ リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="95de7-109">Name of the quota resource.</span></span></param>
        <param name="unit"><span data-ttu-id="95de7-110">クォータ リソースの測定単位です。</span><span class="sxs-lookup"><span data-stu-id="95de7-110">Units of measurement for the quota resource.</span></span></param>
        <param name="currentValue"><span data-ttu-id="95de7-111">リソースのカウンターの現在の値。</span><span class="sxs-lookup"><span data-stu-id="95de7-111">The current value of the resource counter.</span></span></param>
        <param name="limit"><span data-ttu-id="95de7-112">リソースの使用制限します。</span><span class="sxs-lookup"><span data-stu-id="95de7-112">The resource limit.</span></span></param>
        <param name="nextResetTime"><span data-ttu-id="95de7-113">次に、リソースのカウンターの時刻をリセットします。</span><span class="sxs-lookup"><span data-stu-id="95de7-113">Next reset time for the resource counter.</span></span></param>
        <param name="computeMode"><span data-ttu-id="95de7-114">この使用法に使用するモードを計算します。</span><span class="sxs-lookup"><span data-stu-id="95de7-114">Compute mode used for this usage.</span></span>
            <span data-ttu-id="95de7-115">使用可能な値が含まれます: 'Shared'、'Dedicated'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="95de7-115">Possible values include: 'Shared', 'Dedicated', 'Dynamic'</span></span></param>
        <param name="siteMode"><span data-ttu-id="95de7-116">この使用法に使用するサイト モードです。</span><span class="sxs-lookup"><span data-stu-id="95de7-116">Site mode used for this usage.</span></span></param>
        <summary>
            <span data-ttu-id="95de7-117">使用状況のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="95de7-117">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt; ComputeMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.ComputeMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeMode As Nullable(Of ComputeModeOptions)" />
      <MemberSignature Language="F#" Value="member this.ComputeMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.ComputeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computeMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ComputeModeOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-118">取得では、この使用法に使用するモードを計算します。</span><span class="sxs-lookup"><span data-stu-id="95de7-118">Gets compute mode used for this usage.</span></span> <span data-ttu-id="95de7-119">使用可能な値が含まれます: 'Shared'、'Dedicated'、'Dynamic'</span><span class="sxs-lookup"><span data-stu-id="95de7-119">Possible values include: 'Shared', 'Dedicated', 'Dynamic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-120">リソースのカウンターの現在の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-120">Gets the current value of the resource counter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-121">UI に表示されるフレンドリ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-121">Gets friendly name shown in the UI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-122">リソースの制限値を取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-122">Gets the resource limit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextResetTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextResetTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextResetTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.NextResetTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextResetTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextResetTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.NextResetTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextResetTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-123">リソース カウンターのリセットの次の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-123">Gets next reset time for the resource counter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.ResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-124">クォータ リソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-124">Gets name of the quota resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteMode">
      <MemberSignature Language="C#" Value="public string SiteMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.SiteMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SiteMode As String" />
      <MemberSignature Language="F#" Value="member this.SiteMode : string" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.SiteMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-125">この使用法に使用するサイト モードを取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-125">Gets site mode used for this usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95de7-126">クォータ リソースの測定単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-126">Gets units of measurement for the quota resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageName">
      <MemberSignature Language="C#" Value="public string UsageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Usage.UsageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageName As String" />
      <MemberSignature Language="F#" Value="member this.UsageName : string" Usage="Microsoft.Azure.Management.WebSites.Models.Usage.UsageName" />
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
            <span data-ttu-id="95de7-127">クォータの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="95de7-127">Gets name of the quota.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>