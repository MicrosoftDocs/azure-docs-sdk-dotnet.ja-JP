<Type Name="WebhookUpdateParameters" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters">
  <TypeSignature Language="C#" Value="public class WebhookUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebhookUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class WebhookUpdateParameters" />
  <TypeSignature Language="F#" Value="type WebhookUpdateParameters = class" />
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
            <span data-ttu-id="f90c9-101">Webhook を更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f90c9-101">The parameters for updating a webhook.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f90c9-102">WebhookUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-102">Initializes a new instance of the WebhookUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebhookUpdateParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string serviceUri = null, System.Collections.Generic.IDictionary&lt;string,string&gt; customHeaders = null, string status = null, string scope = null, System.Collections.Generic.IList&lt;string&gt; actions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string serviceUri, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; customHeaders, string status, string scope, class System.Collections.Generic.IList`1&lt;string&gt; actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional serviceUri As String = null, Optional customHeaders As IDictionary(Of String, String) = null, Optional status As String = null, Optional scope As String = null, Optional actions As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters (tags, serviceUri, customHeaders, status, scope, actions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="serviceUri" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="actions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="f90c9-103">Webhook のタグ。</span><span class="sxs-lookup"><span data-stu-id="f90c9-103">The tags for the webhook.</span></span></param>
        <param name="serviceUri"><span data-ttu-id="f90c9-104">サービスの通知を送信する webhook の URI です。</span><span class="sxs-lookup"><span data-stu-id="f90c9-104">The service URI for the webhook to post notifications.</span></span></param>
        <param name="customHeaders"><span data-ttu-id="f90c9-105">Webhook 通知に追加されるカスタム ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="f90c9-105">Custom headers that will be added to the webhook notifications.</span></span></param>
        <param name="status"><span data-ttu-id="f90c9-106">操作が呼び出されたときに webhook の状態です。</span><span class="sxs-lookup"><span data-stu-id="f90c9-106">The status of the webhook at the time the operation was called.</span></span> <span data-ttu-id="f90c9-107">使用可能な値が含まれます: 'enabled'、'disabled'</span><span class="sxs-lookup"><span data-stu-id="f90c9-107">Possible values include: 'enabled', 'disabled'</span></span></param>
        <param name="scope"><span data-ttu-id="f90c9-108">イベントをトリガーできますリポジトリのスコープです。</span><span class="sxs-lookup"><span data-stu-id="f90c9-108">The scope of repositories where the event can be triggered.</span></span> <span data-ttu-id="f90c9-109">たとえば、' foo: \*' リポジトリ foo 下にあるすべてのタグ イベントのことを意味します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-109">For example, 'foo:\*' means events for all tags under repository 'foo'.</span></span> <span data-ttu-id="f90c9-110">'foo:bar' は、'foo:bar' のみのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-110">'foo:bar' means events for 'foo:bar' only.</span></span> <span data-ttu-id="f90c9-111">'foo' は、'foo:latest' と同じです。</span><span class="sxs-lookup"><span data-stu-id="f90c9-111">'foo' is equivalent to 'foo:latest'.</span></span> <span data-ttu-id="f90c9-112">空では、すべてのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-112">Empty means all events.</span></span></param>
        <param name="actions"><span data-ttu-id="f90c9-113">通知を送信する webhook をトリガーするアクションの一覧。</span><span class="sxs-lookup"><span data-stu-id="f90c9-113">The list of actions that trigger the webhook to post notifications.</span></span></param>
        <summary>
            <span data-ttu-id="f90c9-114">WebhookUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-114">Initializes a new instance of the WebhookUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Actions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Actions" />
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
            <span data-ttu-id="f90c9-115">取得または通知を送信する webhook をトリガーするアクションの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-115">Gets or sets the list of actions that trigger the webhook to post notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; CustomHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; CustomHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.CustomHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomHeaders As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.CustomHeaders : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.CustomHeaders" />
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
            <span data-ttu-id="f90c9-116">取得または webhook 通知に追加されるカスタム ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-116">Gets or sets custom headers that will be added to the webhook notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Scope" />
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
            <span data-ttu-id="f90c9-117">取得またはイベントをトリガーできますリポジトリのスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-117">Gets or sets the scope of repositories where the event can be triggered.</span></span> <span data-ttu-id="f90c9-118">たとえば、' foo: \*' リポジトリ foo 下にあるすべてのタグ イベントのことを意味します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-118">For example, 'foo:\*' means events for all tags under repository 'foo'.</span></span> <span data-ttu-id="f90c9-119">'foo:bar' は、'foo:bar' のみのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-119">'foo:bar' means events for 'foo:bar' only.</span></span> <span data-ttu-id="f90c9-120">'foo' は、'foo:latest' と同じです。</span><span class="sxs-lookup"><span data-stu-id="f90c9-120">'foo' is equivalent to 'foo:latest'.</span></span> <span data-ttu-id="f90c9-121">空では、すべてのイベントを意味します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-121">Empty means all events.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public string ServiceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceUri As String" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.ServiceUri" />
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
            <span data-ttu-id="f90c9-122">取得またはサービスの通知を送信する webhook の URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-122">Gets or sets the service URI for the webhook to post notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Status" />
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
            <span data-ttu-id="f90c9-123">取得または操作が呼び出された時点で、webhook の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-123">Gets or sets the status of the webhook at the time the operation was called.</span></span> <span data-ttu-id="f90c9-124">使用可能な値が含まれます: 'enabled'、'disabled'</span><span class="sxs-lookup"><span data-stu-id="f90c9-124">Possible values include: 'enabled', 'disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters.Tags" />
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
            <span data-ttu-id="f90c9-125">取得または webhook のタグを設定します。</span><span class="sxs-lookup"><span data-stu-id="f90c9-125">Gets or sets the tags for the webhook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>