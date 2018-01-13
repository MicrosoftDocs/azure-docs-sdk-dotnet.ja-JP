<Type Name="ValidateRequest" FullName="Microsoft.Azure.Management.WebSites.Models.ValidateRequest">
  <TypeSignature Language="C#" Value="public class ValidateRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateRequest" />
  <TypeSignature Language="F#" Value="type ValidateRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="daba5-101">リソースの検証要求の内容。</span><span class="sxs-lookup"><span data-stu-id="daba5-101">Resource validation request content.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="daba5-102">クロス クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="daba5-102">Initializes a new instance of the ValidateRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateRequest (string name, string type, string location, string serverFarmId = null, string skuName = null, Nullable&lt;bool&gt; needLinuxWorkers = null, Nullable&lt;bool&gt; isSpot = null, Nullable&lt;int&gt; capacity = null, string hostingEnvironment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, string location, string serverFarmId, string skuName, valuetype System.Nullable`1&lt;bool&gt; needLinuxWorkers, valuetype System.Nullable`1&lt;bool&gt; isSpot, valuetype System.Nullable`1&lt;int32&gt; capacity, string hostingEnvironment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As String, location As String, Optional serverFarmId As String = null, Optional skuName As String = null, Optional needLinuxWorkers As Nullable(Of Boolean) = null, Optional isSpot As Nullable(Of Boolean) = null, Optional capacity As Nullable(Of Integer) = null, Optional hostingEnvironment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ValidateRequest : string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.ValidateRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.ValidateRequest (name, type, location, serverFarmId, skuName, needLinuxWorkers, isSpot, capacity, hostingEnvironment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="skuName" Type="System.String" />
        <Parameter Name="needLinuxWorkers" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isSpot" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="daba5-103">リソース名を確認してください。</span><span class="sxs-lookup"><span data-stu-id="daba5-103">Resource name to verify.</span></span></param>
        <param name="type"><span data-ttu-id="daba5-104">リソースの種類の検証に使用します。</span><span class="sxs-lookup"><span data-stu-id="daba5-104">Resource type used for verification.</span></span> <span data-ttu-id="daba5-105">使用可能な値が含まれます: 'ServerFarm'、'サイト'</span><span class="sxs-lookup"><span data-stu-id="daba5-105">Possible values include: 'ServerFarm', 'Site'</span></span></param>
        <param name="location"><span data-ttu-id="daba5-106">リソースの予期される場所です。</span><span class="sxs-lookup"><span data-stu-id="daba5-106">Expected location of the resource.</span></span></param>
        <param name="serverFarmId"><span data-ttu-id="daba5-107">アプリをホストする App Service プランの ARM リソース ID です。</span><span class="sxs-lookup"><span data-stu-id="daba5-107">ARM resource ID of an App Service plan that would host the app.</span></span></param>
        <param name="skuName"><span data-ttu-id="daba5-108">App Service プランのターゲットの SKU の名前です。</span><span class="sxs-lookup"><span data-stu-id="daba5-108">Name of the target SKU for the App Service plan.</span></span></param>
        <param name="needLinuxWorkers"><span data-ttu-id="daba5-109">&lt;コード&gt;true&lt;/code&gt; App Service プランが Linux ワーカー以外の場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="daba5-109">&lt;code&gt;true&lt;/code&gt; if App Service plan is for Linux workers; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="isSpot"><span data-ttu-id="daba5-110">&lt;コード&gt;true&lt;/code&gt; App Service プランがスポット インスタンス以外の場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="daba5-110">&lt;code&gt;true&lt;/code&gt; if App Service plan is for Spot instances; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="capacity"><span data-ttu-id="daba5-111">App Service プラン (VM の数) の容量を対象します。</span><span class="sxs-lookup"><span data-stu-id="daba5-111">Target capacity of the App Service plan (number of VM's).</span></span></param>
        <param name="hostingEnvironment"><span data-ttu-id="daba5-112">アプリまたは App Service プランを作成する必要が App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="daba5-112">Name of App Service Environment where app or App Service plan should be created.</span></span></param>
        <summary>
            <span data-ttu-id="daba5-113">クロス クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="daba5-113">Initializes a new instance of the ValidateRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daba5-114">取得または App Service プラン (VM の数) の容量のターゲットを設定します。</span><span class="sxs-lookup"><span data-stu-id="daba5-114">Gets or sets target capacity of the App Service plan (number of VM's).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daba5-115">取得またはアプリまたは App Service プランを作成する必要が App Service 環境の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="daba5-115">Gets or sets name of App Service Environment where app or App Service plan should be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSpot">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSpot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSpot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.IsSpot" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSpot As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSpot : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.IsSpot" />
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
            <span data-ttu-id="daba5-116">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; App Service プランがスポット インスタンス以外の場合それ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp; 。gt;。</span><span class="sxs-lookup"><span data-stu-id="daba5-116">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if App Service plan is for Spot instances; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daba5-117">取得またはリソースの予期される場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="daba5-117">Gets or sets expected location of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Name" />
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
            <span data-ttu-id="daba5-118">取得または設定を確認するリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="daba5-118">Gets or sets resource name to verify.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NeedLinuxWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NeedLinuxWorkers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NeedLinuxWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.NeedLinuxWorkers" />
      <MemberSignature Language="VB.NET" Value="Public Property NeedLinuxWorkers As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NeedLinuxWorkers : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.NeedLinuxWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.needLinuxWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daba5-119">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; App Service プランが Linux ワーカー以外の場合それ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt。;.</span><span class="sxs-lookup"><span data-stu-id="daba5-119">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if App Service plan is for Linux workers; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daba5-120">取得またはアプリケーションをホストする App Service プランの ARM リソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="daba5-120">Gets or sets ARM resource ID of an App Service plan that would host the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkuName">
      <MemberSignature Language="C#" Value="public string SkuName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SkuName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.SkuName" />
      <MemberSignature Language="VB.NET" Value="Public Property SkuName As String" />
      <MemberSignature Language="F#" Value="member this.SkuName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.SkuName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.skuName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="daba5-121">取得または設定のターゲットの SKU を App Service プランの名前。</span><span class="sxs-lookup"><span data-stu-id="daba5-121">Gets or sets name of the target SKU for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="daba5-122">取得または設定の検証に使用するリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="daba5-122">Gets or sets resource type used for verification.</span></span> <span data-ttu-id="daba5-123">使用可能な値が含まれます: 'ServerFarm'、'サイト'</span><span class="sxs-lookup"><span data-stu-id="daba5-123">Possible values include: 'ServerFarm', 'Site'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="validateRequest.Validate " />
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
            <span data-ttu-id="daba5-124">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="daba5-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="daba5-125">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="daba5-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>