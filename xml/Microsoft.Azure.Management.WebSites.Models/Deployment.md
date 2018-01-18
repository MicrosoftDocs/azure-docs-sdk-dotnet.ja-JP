<Type Name="Deployment" FullName="Microsoft.Azure.Management.WebSites.Models.Deployment">
  <TypeSignature Language="C#" Value="public class Deployment : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Deployment extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Deployment" />
  <TypeSignature Language="VB.NET" Value="Public Class Deployment&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type Deployment = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="c1490-101">アクティビティのパブリッシュに使用されるユーザー crendentials です。</span><span class="sxs-lookup"><span data-stu-id="c1490-101">User crendentials used for publishing activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Deployment ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Deployment.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c1490-102">Deployment クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c1490-102">Initializes a new instance of the Deployment class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Deployment (string id = null, string name = null, string kind = null, string type = null, string deploymentId = null, Nullable&lt;int&gt; status = null, string message = null, string author = null, string deployer = null, string authorEmail = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;bool&gt; active = null, string details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string deploymentId, valuetype System.Nullable`1&lt;int32&gt; status, string message, string author, string deployer, string authorEmail, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;bool&gt; active, string details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Deployment.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional deploymentId As String = null, Optional status As Nullable(Of Integer) = null, Optional message As String = null, Optional author As String = null, Optional deployer As String = null, Optional authorEmail As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional active As Nullable(Of Boolean) = null, Optional details As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Deployment : string * string * string * string * string * Nullable&lt;int&gt; * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.Deployment" Usage="new Microsoft.Azure.Management.WebSites.Models.Deployment (id, name, kind, type, deploymentId, status, message, author, deployer, authorEmail, startTime, endTime, active, details)" />
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
        <Parameter Name="deploymentId" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="author" Type="System.String" />
        <Parameter Name="deployer" Type="System.String" />
        <Parameter Name="authorEmail" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="active" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="details" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="c1490-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="c1490-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="c1490-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="c1490-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="c1490-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c1490-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="c1490-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c1490-106">Resource type.</span></span></param>
        <param name="deploymentId"><span data-ttu-id="c1490-107">デプロイの識別子。</span><span class="sxs-lookup"><span data-stu-id="c1490-107">Identifier for deployment.</span></span></param>
        <param name="status"><span data-ttu-id="c1490-108">展開のステータス。</span><span class="sxs-lookup"><span data-stu-id="c1490-108">Deployment status.</span></span></param>
        <param name="message"><span data-ttu-id="c1490-109">展開のステータスについての詳細。</span><span class="sxs-lookup"><span data-stu-id="c1490-109">Details about deployment status.</span></span></param>
        <param name="author"><span data-ttu-id="c1490-110">ユーザーには、展開が作成されたためです。</span><span class="sxs-lookup"><span data-stu-id="c1490-110">Who authored the deployment.</span></span></param>
        <param name="deployer"><span data-ttu-id="c1490-111">展開を実行したユーザー。</span><span class="sxs-lookup"><span data-stu-id="c1490-111">Who performed the deployment.</span></span></param>
        <param name="authorEmail"><span data-ttu-id="c1490-112">作成者の電子メール アドレス。</span><span class="sxs-lookup"><span data-stu-id="c1490-112">Author email.</span></span></param>
        <param name="startTime"><span data-ttu-id="c1490-113">開始時刻。</span><span class="sxs-lookup"><span data-stu-id="c1490-113">Start time.</span></span></param>
        <param name="endTime"><span data-ttu-id="c1490-114">終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="c1490-114">End time.</span></span></param>
        <param name="active"><span data-ttu-id="c1490-115">展開が現在アクティブな場合、false が完了した場合は true、開始されていない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="c1490-115">True if deployment is currently active, false if completed and null if not started.</span></span></param>
        <param name="details"><span data-ttu-id="c1490-116">展開について説明します。</span><span class="sxs-lookup"><span data-stu-id="c1490-116">Details on deployment.</span></span></param>
        <summary>
            <span data-ttu-id="c1490-117">Deployment クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c1490-117">Initializes a new instance of the Deployment class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Active { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Active" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.Active" />
      <MemberSignature Language="VB.NET" Value="Public Property Active As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Active : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.Active" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.active")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-118">取得または開始されていない場合は、展開によりアクティブ、完了した場合は false、および null では現在は true を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-118">Gets or sets true if deployment is currently active, false if completed and null if not started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Author">
      <MemberSignature Language="C#" Value="public string Author { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Author" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.Author" />
      <MemberSignature Language="VB.NET" Value="Public Property Author As String" />
      <MemberSignature Language="F#" Value="member this.Author : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.Author" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.author")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-119">取得または展開を作成したユーザーを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-119">Gets or sets who authored the deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorEmail">
      <MemberSignature Language="C#" Value="public string AuthorEmail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorEmail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.AuthorEmail" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorEmail As String" />
      <MemberSignature Language="F#" Value="member this.AuthorEmail : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.AuthorEmail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorEmail")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-120">取得または作成者の電子メールを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-120">Gets or sets author email.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deployer">
      <MemberSignature Language="C#" Value="public string Deployer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Deployer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.Deployer" />
      <MemberSignature Language="VB.NET" Value="Public Property Deployer As String" />
      <MemberSignature Language="F#" Value="member this.Deployer : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.Deployer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deployer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-121">取得または展開を実行したユーザーを設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-121">Gets or sets who performed the deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentId">
      <MemberSignature Language="C#" Value="public string DeploymentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.DeploymentId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentId As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.DeploymentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-122">取得またはデプロイの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-122">Gets or sets identifier for deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-123">取得または展開の詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-123">Gets or sets details on deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-124">取得または終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-124">Gets or sets end time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-125">取得または展開のステータスに関する詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-125">Gets or sets details about deployment status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-126">取得または開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-126">Gets or sets start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Deployment.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.Deployment.Status" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1490-127">取得または展開の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="c1490-127">Gets or sets deployment status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>