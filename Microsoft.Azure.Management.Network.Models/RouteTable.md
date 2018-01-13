<Type Name="RouteTable" FullName="Microsoft.Azure.Management.Network.Models.RouteTable">
  <TypeSignature Language="C#" Value="public class RouteTable : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RouteTable extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.RouteTable" />
  <TypeSignature Language="VB.NET" Value="Public Class RouteTable&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RouteTable = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4d9f6-101">テーブル リソースをルーティングします。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-101">Route table resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.RouteTable.#ctor" />
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
            <span data-ttu-id="4d9f6-102">RouteTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-102">Initializes a new instance of the RouteTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteTable (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Route&gt; routes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets = null, Nullable&lt;bool&gt; disableBgpRoutePropagation = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Route&gt; routes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets, valuetype System.Nullable`1&lt;bool&gt; disableBgpRoutePropagation, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.RouteTable.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Route},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Subnet},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional routes As IList(Of Route) = null, Optional subnets As IList(Of Subnet) = null, Optional disableBgpRoutePropagation As Nullable(Of Boolean) = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.RouteTable : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Route&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Network.Models.RouteTable" Usage="new Microsoft.Azure.Management.Network.Models.RouteTable (id, name, type, location, tags, routes, subnets, disableBgpRoutePropagation, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="routes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Route&gt;" />
        <Parameter Name="subnets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" />
        <Parameter Name="disableBgpRoutePropagation" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="4d9f6-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="4d9f6-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="4d9f6-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="4d9f6-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="4d9f6-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="4d9f6-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-107">Resource tags.</span></span></param>
        <param name="routes"><span data-ttu-id="4d9f6-108">ルート テーブル内に含まれるルートのコレクション。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-108">Collection of routes contained within a route table.</span></span></param>
        <param name="subnets"><span data-ttu-id="4d9f6-109">サブネットへの参照のコレクション。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-109">A collection of references to subnets.</span></span></param>
        <param name="disableBgpRoutePropagation"><span data-ttu-id="4d9f6-110">取得または、そのルート テーブルに対する BGP で学習したルートを無効にするかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-110">Gets or sets whether to disable the routes learned by BGP on that route table.</span></span> <span data-ttu-id="4d9f6-111">True は、無効にすることを意味します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-111">True means disable.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="4d9f6-112">リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-112">The provisioning state of the resource.</span></span> <span data-ttu-id="4d9f6-113">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-113">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="4d9f6-114">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-114">Gets a unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="4d9f6-115">RouteTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-115">Initializes a new instance of the RouteTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableBgpRoutePropagation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisableBgpRoutePropagation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisableBgpRoutePropagation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteTable.DisableBgpRoutePropagation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableBgpRoutePropagation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisableBgpRoutePropagation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.RouteTable.DisableBgpRoutePropagation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.disableBgpRoutePropagation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d9f6-116">取得または、そのルート テーブルに対する BGP で学習したルートを無効にするかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-116">Gets or sets whether to disable the routes learned by BGP on that route table.</span></span> <span data-ttu-id="4d9f6-117">True は、無効にすることを意味します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-117">True means disable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteTable.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.RouteTable.Etag" />
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
            <span data-ttu-id="4d9f6-118">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-118">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteTable.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.RouteTable.ProvisioningState" />
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
            <span data-ttu-id="4d9f6-119">取得またはリソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-119">Gets or sets the provisioning state of the resource.</span></span> <span data-ttu-id="4d9f6-120">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-120">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Route&gt; Routes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Route&gt; Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteTable.Routes" />
      <MemberSignature Language="VB.NET" Value="Public Property Routes As IList(Of Route)" />
      <MemberSignature Language="F#" Value="member this.Routes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Route&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.RouteTable.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Route&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d9f6-121">取得または、ルート テーブル内に含まれるルートのコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-121">Gets or sets collection of routes contained within a route table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteTable.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subnets As IList(Of Subnet)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" Usage="Microsoft.Azure.Management.Network.Models.RouteTable.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d9f6-122">サブネットへの参照のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="4d9f6-122">Gets a collection of references to subnets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>