<Type Name="WebhookCreateParameters" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters">
  <TypeSignature Language="C#" Value="public class WebhookCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebhookCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class WebhookCreateParameters" />
  <TypeSignature Language="F#" Value="type WebhookCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c4bd7-101">Webhook を作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-101">The parameters for creating a webhook.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4bd7-102">WebhookCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-102">Initializes a new instance of the WebhookCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookCreateParameters (string location, string serviceUri, System.Collections.Generic.IList&lt;string&gt; actions, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IDictionary&lt;string,string&gt; customHeaders = null, string status = null, string scope = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string serviceUri, class System.Collections.Generic.IList`1&lt;string&gt; actions, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; customHeaders, string status, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, serviceUri As String, actions As IList(Of String), Optional tags As IDictionary(Of String, String) = null, Optional customHeaders As IDictionary(Of String, String) = null, Optional status As String = null, Optional scope As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters (location, serviceUri, actions, tags, customHeaders, status, scope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="serviceUri" Type="System.String" />
        <Parameter Name="actions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="c4bd7-103">Webhook の場所です。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-103">The location of the webhook.</span></span> <span data-ttu-id="c4bd7-104">これは、リソースを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-104">This cannot be changed after the resource is created.</span></span></param>
        <param name="serviceUri"><span data-ttu-id="c4bd7-105">サービスの通知を送信する webhook の URI です。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-105">The service URI for the webhook to post notifications.</span></span></param>
        <param name="actions"><span data-ttu-id="c4bd7-106">通知を送信する webhook をトリガーするアクションの一覧。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-106">The list of actions that trigger the webhook to post notifications.</span></span></param>
        <param name="tags"><span data-ttu-id="c4bd7-107">Webhook のタグ。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-107">The tags for the webhook.</span></span></param>
        <param name="customHeaders"><span data-ttu-id="c4bd7-108">Webhook 通知に追加されるカスタム ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-108">Custom headers that will be added to the webhook notifications.</span></span></param>
        <param name="status"><span data-ttu-id="c4bd7-109">操作が呼び出されたときに webhook の状態です。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-109">The status of the webhook at the time the operation was called.</span></span> <span data-ttu-id="c4bd7-110">使用可能な値が含まれます: 'enabled'、'disabled'</span><span class="sxs-lookup"><span data-stu-id="c4bd7-110">Possible values include: 'enabled', 'disabled'</span></span></param>
        <param name="scope"><span data-ttu-id="c4bd7-111">イベントをトリガーできますリポジトリのスコープです。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-111">The scope of repositories where the event can be triggered.</span></span> <span data-ttu-id="c4bd7-112">たとえば、' foo: \*' リポジトリ foo 下にあるすべてのタグ イベントのことを意味します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-112">For example, 'foo:\*' means events for all tags under repository 'foo'.</span></span> <span data-ttu-id="c4bd7-113">'foo:bar' は、'foo:bar' のみのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-113">'foo:bar' means events for 'foo:bar' only.</span></span> <span data-ttu-id="c4bd7-114">'foo' は、'foo:latest' と同じです。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-114">'foo' is equivalent to 'foo:latest'.</span></span> <span data-ttu-id="c4bd7-115">空では、すべてのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-115">Empty means all events.</span></span></param>
        <summary>
            <span data-ttu-id="c4bd7-116">WebhookCreateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-116">Initializes a new instance of the WebhookCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Actions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Actions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.actions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4bd7-117">取得または通知を送信する webhook をトリガーするアクションの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-117">Gets or sets the list of actions that trigger the webhook to post notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; CustomHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; CustomHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.CustomHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomHeaders As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.CustomHeaders : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.CustomHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customHeaders")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4bd7-118">取得または webhook 通知に追加されるカスタム ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-118">Gets or sets custom headers that will be added to the webhook notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c4bd7-119">取得または webhook の場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-119">Gets or sets the location of the webhook.</span></span> <span data-ttu-id="c4bd7-120">これは、リソースを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-120">This cannot be changed after the resource is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4bd7-121">取得またはイベントをトリガーできますリポジトリのスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-121">Gets or sets the scope of repositories where the event can be triggered.</span></span> <span data-ttu-id="c4bd7-122">たとえば、' foo: \*' リポジトリ foo 下にあるすべてのタグ イベントのことを意味します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-122">For example, 'foo:\*' means events for all tags under repository 'foo'.</span></span> <span data-ttu-id="c4bd7-123">'foo:bar' は、'foo:bar' のみのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-123">'foo:bar' means events for 'foo:bar' only.</span></span> <span data-ttu-id="c4bd7-124">'foo' は、'foo:latest' と同じです。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-124">'foo' is equivalent to 'foo:latest'.</span></span> <span data-ttu-id="c4bd7-125">空では、すべてのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-125">Empty means all events.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public string ServiceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceUri As String" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4bd7-126">取得またはサービスの通知を送信する webhook の URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-126">Gets or sets the service URI for the webhook to post notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4bd7-127">取得または操作が呼び出された時点で、webhook の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-127">Gets or sets the status of the webhook at the time the operation was called.</span></span> <span data-ttu-id="c4bd7-128">使用可能な値が含まれます: 'enabled'、'disabled'</span><span class="sxs-lookup"><span data-stu-id="c4bd7-128">Possible values include: 'enabled', 'disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c4bd7-129">取得または webhook のタグを設定します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-129">Gets or sets the tags for the webhook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="webhookCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4bd7-130">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-130">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c4bd7-131">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c4bd7-131">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>