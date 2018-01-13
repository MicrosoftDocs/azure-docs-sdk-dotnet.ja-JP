<Type Name="PatchRouteFilterInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner">
  <TypeSignature Language="C#" Value="public class PatchRouteFilterInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatchRouteFilterInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner" />
  <TypeSignature Language="VB.NET" Value="Public Class PatchRouteFilterInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type PatchRouteFilterInner = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="c08c7-101">ルート フィルターのリソースです。</span><span class="sxs-lookup"><span data-stu-id="c08c7-101">Route Filter Resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatchRouteFilterInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c08c7-102">PatchRouteFilterInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-102">Initializes a new instance of the PatchRouteFilterInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatchRouteFilterInner (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; rules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; peerings = null, string provisioningState = null, string name = null, string etag = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; rules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; peerings, string provisioningState, string name, string etag, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional rules As IList(Of RouteFilterRuleInner) = null, Optional peerings As IList(Of ExpressRouteCircuitPeeringInner) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner (id, rules, peerings, provisioningState, name, etag, type, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" />
        <Parameter Name="peerings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="rules"><span data-ttu-id="c08c7-103">ルート フィルター内に含まれる RouteFilterRules のコレクションです。</span><span class="sxs-lookup"><span data-stu-id="c08c7-103">Collection of RouteFilterRules contained within a route filter.</span></span></param>
        <param name="peerings"><span data-ttu-id="c08c7-104">Express route 回線ピアリングへの参照のコレクション。</span><span class="sxs-lookup"><span data-stu-id="c08c7-104">A collection of references to express route circuit peerings.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="c08c7-105">リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="c08c7-105">The provisioning state of the resource.</span></span> <span data-ttu-id="c08c7-106">使用可能な値が: '更新'、'削除'、'成功' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="c08c7-106">Possible values are: 'Updating', 'Deleting', 'Succeeded' and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="c08c7-107">リソース グループ内で一意であるリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="c08c7-107">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="c08c7-108">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="c08c7-108">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="c08c7-109">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-109">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="type"><span data-ttu-id="c08c7-110">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c08c7-110">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="c08c7-111">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="c08c7-111">Resource tags.</span></span></param>
        <summary>
            <span data-ttu-id="c08c7-112">PatchRouteFilterInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-112">Initializes a new instance of the PatchRouteFilterInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Etag" />
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
            <span data-ttu-id="c08c7-113">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-113">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Name" />
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
            <span data-ttu-id="c08c7-114">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-114">Gets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="c08c7-115">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="c08c7-115">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peerings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; Peerings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; Peerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Peerings" />
      <MemberSignature Language="VB.NET" Value="Public Property Peerings As IList(Of ExpressRouteCircuitPeeringInner)" />
      <MemberSignature Language="F#" Value="member this.Peerings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Peerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peerings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c08c7-116">Express route 回線ピアリングへの参照のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-116">Gets a collection of references to express route circuit peerings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.ProvisioningState" />
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
            <span data-ttu-id="c08c7-117">リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-117">Gets the provisioning state of the resource.</span></span> <span data-ttu-id="c08c7-118">使用可能な値が: '更新'、'削除'、'成功' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="c08c7-118">Possible values are: 'Updating', 'Deleting', 'Succeeded' and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of RouteFilterRuleInner)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c08c7-119">取得またはルート フィルター内に含まれる RouteFilterRules のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-119">Gets or sets collection of RouteFilterRules contained within a route filter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Tags" />
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
            <span data-ttu-id="c08c7-120">取得またはリソース タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-120">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c08c7-121">リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="c08c7-121">Gets resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>