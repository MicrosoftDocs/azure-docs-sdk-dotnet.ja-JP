<Type Name="RecommendationRule" FullName="Microsoft.Azure.Management.WebSites.Models.RecommendationRule">
  <TypeSignature Language="C#" Value="public class RecommendationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendationRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RecommendationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendationRule" />
  <TypeSignature Language="F#" Value="type RecommendationRule = class" />
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
            <span data-ttu-id="ff8c0-101">リコメンデーション エンジンを実行できるリコメンデーション ルールを表します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-101">Represents a recommendation rule that the recommendation engine can perform.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendationRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-102">RecommendationRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-102">Initializes a new instance of the RecommendationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendationRule (string name = null, string displayName = null, string message = null, Nullable&lt;Guid&gt; recommendationId = null, string description = null, string actionName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; level = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; channels = null, System.Collections.Generic.IList&lt;string&gt; tags = null, Nullable&lt;bool&gt; isDynamic = null, string extensionName = null, string bladeName = null, string forwardLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string message, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; recommendationId, string description, string actionName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; level, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.Channels&gt; channels, class System.Collections.Generic.IList`1&lt;string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; isDynamic, string extensionName, string bladeName, string forwardLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.#ctor(System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.NotificationLevel},System.Nullable{Microsoft.Azure.Management.WebSites.Models.Channels},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional message As String = null, Optional recommendationId As Nullable(Of Guid) = null, Optional description As String = null, Optional actionName As String = null, Optional level As Nullable(Of NotificationLevel) = null, Optional channels As Nullable(Of Channels) = null, Optional tags As IList(Of String) = null, Optional isDynamic As Nullable(Of Boolean) = null, Optional extensionName As String = null, Optional bladeName As String = null, Optional forwardLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RecommendationRule : string * string * string * Nullable&lt;Guid&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.RecommendationRule" Usage="new Microsoft.Azure.Management.WebSites.Models.RecommendationRule (name, displayName, message, recommendationId, description, actionName, level, channels, tags, isDynamic, extensionName, bladeName, forwardLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="recommendationId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="actionName" Type="System.String" />
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt;" />
        <Parameter Name="channels" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isDynamic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="extensionName" Type="System.String" />
        <Parameter Name="bladeName" Type="System.String" />
        <Parameter Name="forwardLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ff8c0-103">規則の一意の名前。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-103">Unique name of the rule.</span></span></param>
        <param name="displayName"><span data-ttu-id="ff8c0-104">規則の UI の表示名。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-104">UI friendly name of the rule.</span></span></param>
        <param name="message"><span data-ttu-id="ff8c0-105">ルール (UI に適している) のローカライズされた名前。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-105">Localized name of the rule (Good for UI).</span></span></param>
        <param name="recommendationId"><span data-ttu-id="ff8c0-106">推奨設定が関連付けられているオブジェクトの ID が、そのルールに関連付けられている場合の推奨設定が存在します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-106">Recommendation ID of an associated recommendation object tied to the rule, if exists.</span></span>
            <span data-ttu-id="ff8c0-107">設定されているようなオブジェクトが存在しない場合に null です。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-107">If such an object doesn't exist, it is set to null.</span></span></param>
        <param name="description"><span data-ttu-id="ff8c0-108">ルールの詳細な説明をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-108">Localized detailed description of the rule.</span></span></param>
        <param name="actionName"><span data-ttu-id="ff8c0-109">文字列でこの規則によって推奨されるアクションの名前。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-109">Name of action that is recommended by this rule in string.</span></span></param>
        <param name="level"><span data-ttu-id="ff8c0-110">このルールは、重大度を示すへの影響のレベルです。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-110">Level of impact indicating how critical this rule is.</span></span> <span data-ttu-id="ff8c0-111">使用可能な値が含まれます: '重大'、'警告'、'情報'、'NonUrgentSuggestion'</span><span class="sxs-lookup"><span data-stu-id="ff8c0-111">Possible values include: 'Critical', 'Warning', 'Information', 'NonUrgentSuggestion'</span></span></param>
        <param name="channels"><span data-ttu-id="ff8c0-112">このルールが適用される利用可能なチャネルのリストです。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-112">List of available channels that this rule applies.</span></span> <span data-ttu-id="ff8c0-113">使用可能な値が含まれます: '通知'、'Api'、'電子メール'、'Webhook'、'All'</span><span class="sxs-lookup"><span data-stu-id="ff8c0-113">Possible values include: 'Notification', 'Api', 'Email', 'Webhook', 'All'</span></span></param>
        <param name="tags"><span data-ttu-id="ff8c0-114">ルールを含むカテゴリのタグの配列。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-114">An array of category tags that the rule contains.</span></span></param>
        <param name="isDynamic"><span data-ttu-id="ff8c0-115">これは、動的に追加された規則に関連付ける場合は true。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-115">True if this is associated with a dynamically added rule</span></span></param>
        <param name="extensionName"><span data-ttu-id="ff8c0-116">場合は、ポータルの拡張機能の名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-116">Extension name of the portal if exists.</span></span>
            <span data-ttu-id="ff8c0-117">ダイナミック ルールのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-117">Applicable to dynamic rule only.</span></span></param>
        <param name="bladeName"><span data-ttu-id="ff8c0-118">ポータルのブレードへのディープ リンクします。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-118">Deep link to a blade on the portal.</span></span>
            <span data-ttu-id="ff8c0-119">ダイナミック ルールのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-119">Applicable to dynamic rule only.</span></span></param>
        <param name="forwardLink"><span data-ttu-id="ff8c0-120">ルールに関連付けられている外部ドキュメントへのリンクを転送します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-120">Forward link to an external document associated with the rule.</span></span> <span data-ttu-id="ff8c0-121">ダイナミック ルールのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-121">Applicable to dynamic rule only.</span></span></param>
        <summary>
            <span data-ttu-id="ff8c0-122">RecommendationRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-122">Initializes a new instance of the RecommendationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionName">
      <MemberSignature Language="C#" Value="public string ActionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ActionName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionName As String" />
      <MemberSignature Language="F#" Value="member this.ActionName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ActionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-123">取得または文字列でこの規則によって推奨されるアクションの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-123">Gets or sets name of action that is recommended by this rule in string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BladeName">
      <MemberSignature Language="C#" Value="public string BladeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BladeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.BladeName" />
      <MemberSignature Language="VB.NET" Value="Public Property BladeName As String" />
      <MemberSignature Language="F#" Value="member this.BladeName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.BladeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bladeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-124">取得またはポータルのブレードをディープ リンクを設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-124">Gets or sets deep link to a blade on the portal.</span></span> <span data-ttu-id="ff8c0-125">ダイナミック ルールのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-125">Applicable to dynamic rule only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Channels">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; Channels { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.Channels&gt; Channels" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Channels" />
      <MemberSignature Language="VB.NET" Value="Public Property Channels As Nullable(Of Channels)" />
      <MemberSignature Language="F#" Value="member this.Channels : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Channels" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="channels")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-126">取得または、この規則が適用される利用可能なチャネルのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-126">Gets or sets list of available channels that this rule applies.</span></span>
            <span data-ttu-id="ff8c0-127">使用可能な値が含まれます: '通知'、'Api'、'電子メール'、'Webhook'、'All'</span><span class="sxs-lookup"><span data-stu-id="ff8c0-127">Possible values include: 'Notification', 'Api', 'Email', 'Webhook', 'All'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-128">取得またはルールのローカライズの詳細な説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-128">Gets or sets localized detailed description of the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-129">取得または規則の UI の表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-129">Gets or sets UI friendly name of the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionName">
      <MemberSignature Language="C#" Value="public string ExtensionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtensionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ExtensionName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionName As String" />
      <MemberSignature Language="F#" Value="member this.ExtensionName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ExtensionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-130">拡張機能の設定を取得または存在する場合は、ポータルの名前。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-130">Gets or sets extension name of the portal if exists.</span></span> <span data-ttu-id="ff8c0-131">ダイナミック ルールのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-131">Applicable to dynamic rule only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardLink">
      <MemberSignature Language="C#" Value="public string ForwardLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ForwardLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardLink As String" />
      <MemberSignature Language="F#" Value="member this.ForwardLink : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ForwardLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="forwardLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-132">取得または転送リンクをルールに関連付けられている外部ドキュメントに設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-132">Gets or sets forward link to an external document associated with the rule.</span></span> <span data-ttu-id="ff8c0-133">ダイナミック ルールのみに適用されます。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-133">Applicable to dynamic rule only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDynamic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-134">取得または設定、これは、動的に追加された規則に関連付ける場合は true。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-134">Gets or sets true if this is associated with a dynamically added rule</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of NotificationLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-135">取得または、このルールは、重大度を示すへの影響のレベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-135">Gets or sets level of impact indicating how critical this rule is.</span></span>
            <span data-ttu-id="ff8c0-136">使用可能な値が含まれます: '重大'、'警告'、'情報'、'NonUrgentSuggestion'</span><span class="sxs-lookup"><span data-stu-id="ff8c0-136">Possible values include: 'Critical', 'Warning', 'Information', 'NonUrgentSuggestion'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-137">取得またはルール (UI に適している) のローカライズされた名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-137">Gets or sets localized name of the rule (Good for UI).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ff8c0-138">取得またはルールの一意の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-138">Gets or sets unique name of the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RecommendationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RecommendationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.RecommendationId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecommendationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RecommendationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.RecommendationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-139">取得または推奨設定が存在する場合、そのルールに関連付けられている推奨事項が関連付けられているオブジェクトの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-139">Gets or sets recommendation ID of an associated recommendation object tied to the rule, if exists.</span></span>
            <span data-ttu-id="ff8c0-140">設定されているようなオブジェクトが存在しない場合に null です。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-140">If such an object doesn't exist, it is set to null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff8c0-141">取得またはルールを含むカテゴリのタグの配列を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff8c0-141">Gets or sets an array of category tags that the rule contains.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>