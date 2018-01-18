<Type Name="WebActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.WebActivity">
  <TypeSignature Language="C#" Value="public class WebActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class WebActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type WebActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("WebActivity")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="85880-101">Web のアクティビティ。</span><span class="sxs-lookup"><span data-stu-id="85880-101">Web activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85880-102">WebActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="85880-102">Initializes a new instance of the WebActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebActivity (string name, string method, object url, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, object headers = null, object body = null, Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication authentication = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; datasets = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; linkedServices = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string method, object url, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, object headers, object body, class Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication authentication, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; datasets, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; linkedServices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivity.#ctor(System.String,System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.DatasetReference},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, method As String, url As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional headers As Object = null, Optional body As Object = null, Optional authentication As WebActivityAuthentication = null, Optional datasets As IList(Of DatasetReference) = null, Optional linkedServices As IList(Of LinkedServiceReference) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebActivity : string * string * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * obj * obj * Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.WebActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebActivity (name, method, url, additionalProperties, description, dependsOn, linkedServiceName, policy, headers, body, authentication, datasets, linkedServices)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="method" Type="System.String" />
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="headers" Type="System.Object" />
        <Parameter Name="body" Type="System.Object" />
        <Parameter Name="authentication" Type="Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication" />
        <Parameter Name="datasets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;" />
        <Parameter Name="linkedServices" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="85880-103">アクティビティ名。</span><span class="sxs-lookup"><span data-stu-id="85880-103">Activity name.</span></span></param>
        <param name="method"><span data-ttu-id="85880-104">ターゲット エンドポイントの rest API のメソッドです。</span><span class="sxs-lookup"><span data-stu-id="85880-104">Rest API method for target endpoint.</span></span> <span data-ttu-id="85880-105">使用可能な値が含まれます 'GET'、'POST'、'PUT'。</span><span class="sxs-lookup"><span data-stu-id="85880-105">Possible values include: 'GET', 'POST', 'PUT'</span></span></param>
        <param name="url"><span data-ttu-id="85880-106">Web のアクティビティのターゲット エンドポイントとパスです。</span><span class="sxs-lookup"><span data-stu-id="85880-106">Web activity target endpoint and path.</span></span> <span data-ttu-id="85880-107">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="85880-107">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="85880-108">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="85880-108">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="85880-109">アクティビティの説明です。</span><span class="sxs-lookup"><span data-stu-id="85880-109">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="85880-110">アクティビティは、条件によって異なります。</span><span class="sxs-lookup"><span data-stu-id="85880-110">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="85880-111">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="85880-111">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="85880-112">アクティビティ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="85880-112">Activity policy.</span></span></param>
        <param name="headers"><span data-ttu-id="85880-113">要求に送信されるヘッダーを表します。</span><span class="sxs-lookup"><span data-stu-id="85880-113">Represents the headers that will be sent to the request.</span></span> <span data-ttu-id="85880-114">たとえば、要求に、言語と種類を設定する:「ヘッダー」: {"Accept Language":"en-us"、「コンテンツの種類」:"application/json"と}。</span><span class="sxs-lookup"><span data-stu-id="85880-114">For example, to set the language and type on a request: "headers" : { "Accept-Language": "en-us", "Content-Type": "application/json" }.</span></span> <span data-ttu-id="85880-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="85880-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="body"><span data-ttu-id="85880-116">エンドポイントに送信されるペイロードを表します。</span><span class="sxs-lookup"><span data-stu-id="85880-116">Represents the payload that will be sent to the endpoint.</span></span> <span data-ttu-id="85880-117">GET メソッドの型に許可されていない、POST または PUT メソッドに必要な: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="85880-117">Required for POST/PUT method, not allowed for GET method Type: string (or Expression with resultType string).</span></span></param>
        <param name="authentication"><span data-ttu-id="85880-118">エンドポイントを呼び出すために使用される認証方法。</span><span class="sxs-lookup"><span data-stu-id="85880-118">Authentication method used for calling the endpoint.</span></span></param>
        <param name="datasets"><span data-ttu-id="85880-119">データセットの一覧は、web エンドポイントに渡されます。</span><span class="sxs-lookup"><span data-stu-id="85880-119">List of datasets passed to web endpoint.</span></span></param>
        <param name="linkedServices"><span data-ttu-id="85880-120">リンクされたサービスの一覧は、web エンドポイントに渡されます。</span><span class="sxs-lookup"><span data-stu-id="85880-120">List of linked services passed to web endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="85880-121">WebActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="85880-121">Initializes a new instance of the WebActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication Authentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication Authentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Authentication" />
      <MemberSignature Language="VB.NET" Value="Public Property Authentication As WebActivityAuthentication" />
      <MemberSignature Language="F#" Value="member this.Authentication : Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Authentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.WebActivityAuthentication</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85880-122">取得またはエンドポイントを呼び出すために使用する認証方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="85880-122">Gets or sets authentication method used for calling the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public object Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As Object" />
      <MemberSignature Language="F#" Value="member this.Body : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85880-123">取得または設定は、エンドポイントに送信されるペイロードを表します。</span><span class="sxs-lookup"><span data-stu-id="85880-123">Gets or sets represents the payload that will be sent to the endpoint.</span></span> <span data-ttu-id="85880-124">GET メソッドの型に許可されていない、POST または PUT メソッドに必要な: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="85880-124">Required for POST/PUT method, not allowed for GET method Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Datasets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public Property Datasets As IList(Of DatasetReference)" />
      <MemberSignature Language="F#" Value="member this.Datasets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.datasets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85880-125">取得または web エンドポイントに渡されるデータセットの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="85880-125">Gets or sets list of datasets passed to web endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public object Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As Object" />
      <MemberSignature Language="F#" Value="member this.Headers : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85880-126">取得または設定は、要求に送信されるヘッダーを表します。</span><span class="sxs-lookup"><span data-stu-id="85880-126">Gets or sets represents the headers that will be sent to the request.</span></span> <span data-ttu-id="85880-127">たとえば、要求に、言語と種類を設定する:「ヘッダー」: {"Accept Language":"en-us"、「コンテンツの種類」:"application/json"と}。</span><span class="sxs-lookup"><span data-stu-id="85880-127">For example, to set the language and type on a request: "headers" : { "Accept-Language": "en-us", "Content-Type": "application/json" }.</span></span> <span data-ttu-id="85880-128">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="85880-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; LinkedServices { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServices As IList(Of LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.linkedServices")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85880-129">取得または web エンドポイントに渡されるリンクされたサービスの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="85880-129">Gets or sets list of linked services passed to web endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Method" />
      <MemberSignature Language="VB.NET" Value="Public Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.method")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85880-130">取得または rest API のメソッドのターゲット エンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="85880-130">Gets or sets rest API method for target endpoint.</span></span> <span data-ttu-id="85880-131">使用可能な値が含まれます 'GET'、'POST'、'PUT'。</span><span class="sxs-lookup"><span data-stu-id="85880-131">Possible values include: 'GET', 'POST', 'PUT'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public object Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As Object" />
      <MemberSignature Language="F#" Value="member this.Url : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebActivity.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85880-132">取得または web のアクティビティのターゲット エンドポイントとパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="85880-132">Gets or sets web activity target endpoint and path.</span></span> <span data-ttu-id="85880-133">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="85880-133">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webActivity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85880-134">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="85880-134">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="85880-135">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="85880-135">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>