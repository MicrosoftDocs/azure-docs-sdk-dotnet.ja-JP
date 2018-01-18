<Type Name="PatchRouteFilterRuleInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner">
  <TypeSignature Language="C#" Value="public class PatchRouteFilterRuleInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi PatchRouteFilterRuleInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" />
  <TypeSignature Language="VB.NET" Value="Public Class PatchRouteFilterRuleInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type PatchRouteFilterRuleInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9d995-101">ルート フィルター ルール リソース</span><span class="sxs-lookup"><span data-stu-id="9d995-101">Route Filter Rule Resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatchRouteFilterRuleInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d995-102">PatchRouteFilterRuleInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9d995-102">Initializes a new instance of the PatchRouteFilterRuleInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatchRouteFilterRuleInner (string access, System.Collections.Generic.IList&lt;string&gt; communities, string id = null, string provisioningState = null, string name = null, string etag = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string access, class System.Collections.Generic.IList`1&lt;string&gt; communities, string id, string provisioningState, string name, string etag, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (access As String, communities As IList(Of String), Optional id As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner : string * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner (access, communities, id, provisioningState, name, etag, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="communities" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="access"><span data-ttu-id="9d995-103">規則のアクセスの種類。</span><span class="sxs-lookup"><span data-stu-id="9d995-103">The access type of the rule.</span></span> <span data-ttu-id="9d995-104">有効な値: 'Allow'、'拒否' です。</span><span class="sxs-lookup"><span data-stu-id="9d995-104">Valid values are: 'Allow', 'Deny'.</span></span> <span data-ttu-id="9d995-105">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="9d995-105">Possible values include: 'Allow', 'Deny'</span></span></param>
        <param name="communities"><span data-ttu-id="9d995-106">フィルターを適用する bgp コミュニティ値のコレクションです。</span><span class="sxs-lookup"><span data-stu-id="9d995-106">The collection for bgp community values to filter on.</span></span> <span data-ttu-id="9d995-107">例: ['12076:5010', '12076:5020']</span><span class="sxs-lookup"><span data-stu-id="9d995-107">e.g. ['12076:5010','12076:5020']</span></span></param>
        <param name="id">To be added.</param>
        <param name="provisioningState"><span data-ttu-id="9d995-108">リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="9d995-108">The provisioning state of the resource.</span></span> <span data-ttu-id="9d995-109">使用可能な値が: '更新'、'削除'、'成功' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="9d995-109">Possible values are: 'Updating', 'Deleting', 'Succeeded' and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="9d995-110">リソース グループ内で一意であるリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="9d995-110">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="9d995-111">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="9d995-111">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="9d995-112">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="9d995-112">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="tags"><span data-ttu-id="9d995-113">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="9d995-113">Resource tags.</span></span></param>
        <summary>
            <span data-ttu-id="9d995-114">PatchRouteFilterRuleInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9d995-114">Initializes a new instance of the PatchRouteFilterRuleInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d995-115">取得または規則のアクセスの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="9d995-115">Gets or sets the access type of the rule.</span></span> <span data-ttu-id="9d995-116">有効な値: 'Allow'、'拒否' です。</span><span class="sxs-lookup"><span data-stu-id="9d995-116">Valid values are: 'Allow', 'Deny'.</span></span> <span data-ttu-id="9d995-117">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="9d995-117">Possible values include: 'Allow', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Communities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Communities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Communities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Communities" />
      <MemberSignature Language="VB.NET" Value="Public Property Communities As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Communities : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Communities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.communities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d995-118">取得または、bgp のコレクションにフィルターを適用するコミュニティの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="9d995-118">Gets or sets the collection for bgp community values to filter on.</span></span>
            <span data-ttu-id="9d995-119">例: ['12076:5010', '12076:5020']</span><span class="sxs-lookup"><span data-stu-id="9d995-119">e.g. ['12076:5010','12076:5020']</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="9d995-120">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d995-120">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="9d995-121">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d995-121">Gets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="9d995-122">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="9d995-122">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="9d995-123">リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d995-123">Gets the provisioning state of the resource.</span></span> <span data-ttu-id="9d995-124">使用可能な値が: '更新'、'削除'、'成功' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="9d995-124">Possible values are: 'Updating', 'Deleting', 'Succeeded' and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilterRuleType">
      <MemberSignature Language="C#" Value="public static string RouteFilterRuleType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string RouteFilterRuleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.RouteFilterRuleType" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property RouteFilterRuleType As String" />
      <MemberSignature Language="F#" Value="member this.RouteFilterRuleType : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.RouteFilterRuleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeFilterRuleType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d995-125">ルールのルールの種類。</span><span class="sxs-lookup"><span data-stu-id="9d995-125">The rule type of the rule.</span></span> <span data-ttu-id="9d995-126">有効な値: 'コミュニティ'</span><span class="sxs-lookup"><span data-stu-id="9d995-126">Valid value is: 'Community'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="9d995-127">取得またはリソース タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="9d995-127">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="patchRouteFilterRuleInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d995-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9d995-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9d995-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9d995-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>