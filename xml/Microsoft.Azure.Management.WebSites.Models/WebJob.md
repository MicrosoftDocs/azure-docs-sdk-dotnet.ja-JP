<Type Name="WebJob" FullName="Microsoft.Azure.Management.WebSites.Models.WebJob">
  <TypeSignature Language="C#" Value="public class WebJob : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebJob extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.WebJob" />
  <TypeSignature Language="VB.NET" Value="Public Class WebJob&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type WebJob = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="70845-101">Web ジョブの情報です。</span><span class="sxs-lookup"><span data-stu-id="70845-101">Web Job Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WebJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="70845-102">Web ジョブ クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="70845-102">Initializes a new instance of the WebJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebJob (string id = null, string name = null, string kind = null, string type = null, string webJobName = null, string runCommand = null, string url = null, string extraInfoUrl = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; jobType = null, string error = null, Nullable&lt;bool&gt; usingSdk = null, System.Collections.Generic.IDictionary&lt;string,object&gt; settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string webJobName, string runCommand, string url, string extraInfoUrl, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; jobType, string error, valuetype System.Nullable`1&lt;bool&gt; usingSdk, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.WebJob.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.WebJobType},System.String,System.Nullable{System.Boolean},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional webJobName As String = null, Optional runCommand As String = null, Optional url As String = null, Optional extraInfoUrl As String = null, Optional jobType As Nullable(Of WebJobType) = null, Optional error As String = null, Optional usingSdk As Nullable(Of Boolean) = null, Optional settings As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.WebJob : string * string * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.WebJob" Usage="new Microsoft.Azure.Management.WebSites.Models.WebJob (id, name, kind, type, webJobName, runCommand, url, extraInfoUrl, jobType, error, usingSdk, settings)" />
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
        <Parameter Name="webJobName" Type="System.String" />
        <Parameter Name="runCommand" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="extraInfoUrl" Type="System.String" />
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt;" />
        <Parameter Name="error" Type="System.String" />
        <Parameter Name="usingSdk" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="70845-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="70845-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="70845-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="70845-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="70845-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="70845-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="70845-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="70845-106">Resource type.</span></span></param>
        <param name="webJobName"><span data-ttu-id="70845-107">ジョブ名です。</span><span class="sxs-lookup"><span data-stu-id="70845-107">Job name.</span></span> <span data-ttu-id="70845-108">ARM リソース URI でジョブの識別子として使用されます。</span><span class="sxs-lookup"><span data-stu-id="70845-108">Used as job identifier in ARM resource URI.</span></span></param>
        <param name="runCommand"><span data-ttu-id="70845-109">コマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="70845-109">Run command.</span></span></param>
        <param name="url"><span data-ttu-id="70845-110">ジョブの URL です。</span><span class="sxs-lookup"><span data-stu-id="70845-110">Job URL.</span></span></param>
        <param name="extraInfoUrl"><span data-ttu-id="70845-111">余分な情報の URL。</span><span class="sxs-lookup"><span data-stu-id="70845-111">Extra Info URL.</span></span></param>
        <param name="jobType"><span data-ttu-id="70845-112">ジョブの種類。</span><span class="sxs-lookup"><span data-stu-id="70845-112">Job type.</span></span> <span data-ttu-id="70845-113">使用可能な値が含まれます: 'Continuous'、'トリガー'</span><span class="sxs-lookup"><span data-stu-id="70845-113">Possible values include: 'Continuous', 'Triggered'</span></span></param>
        <param name="error"><span data-ttu-id="70845-114">エラー情報です。</span><span class="sxs-lookup"><span data-stu-id="70845-114">Error information.</span></span></param>
        <param name="usingSdk"><span data-ttu-id="70845-115">SDK を使用しますか。</span><span class="sxs-lookup"><span data-stu-id="70845-115">Using SDK?</span></span></param>
        <param name="settings"><span data-ttu-id="70845-116">ジョブ設定します。</span><span class="sxs-lookup"><span data-stu-id="70845-116">Job settings.</span></span></param>
        <summary>
            <span data-ttu-id="70845-117">Web ジョブ クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="70845-117">Initializes a new instance of the WebJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70845-118">取得またはエラー情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="70845-118">Gets or sets error information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtraInfoUrl">
      <MemberSignature Language="C#" Value="public string ExtraInfoUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtraInfoUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.ExtraInfoUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtraInfoUrl As String" />
      <MemberSignature Language="F#" Value="member this.ExtraInfoUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.ExtraInfoUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.extraInfoUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70845-119">取得または追加情報の URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="70845-119">Gets or sets extra Info URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As Nullable(Of WebJobType)" />
      <MemberSignature Language="F#" Value="member this.JobType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.WebJobType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70845-120">取得またはジョブの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="70845-120">Gets or sets job type.</span></span> <span data-ttu-id="70845-121">使用可能な値が含まれます: 'Continuous'、'トリガー'</span><span class="sxs-lookup"><span data-stu-id="70845-121">Possible values include: 'Continuous', 'Triggered'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommand">
      <MemberSignature Language="C#" Value="public string RunCommand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunCommand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.RunCommand" />
      <MemberSignature Language="VB.NET" Value="Public Property RunCommand As String" />
      <MemberSignature Language="F#" Value="member this.RunCommand : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.RunCommand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.runCommand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70845-122">取得または設定のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="70845-122">Gets or sets run command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property Settings As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70845-123">取得またはジョブ設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="70845-123">Gets or sets job settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70845-124">取得またはジョブの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="70845-124">Gets or sets job URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsingSdk">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsingSdk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsingSdk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.UsingSdk" />
      <MemberSignature Language="VB.NET" Value="Public Property UsingSdk As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsingSdk : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.UsingSdk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usingSdk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70845-125">取得または SDK を使用して設定しますか。</span><span class="sxs-lookup"><span data-stu-id="70845-125">Gets or sets using SDK?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebJobName">
      <MemberSignature Language="C#" Value="public string WebJobName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WebJobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.WebJob.WebJobName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebJobName As String" />
      <MemberSignature Language="F#" Value="member this.WebJobName : string" Usage="Microsoft.Azure.Management.WebSites.Models.WebJob.WebJobName" />
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
            <span data-ttu-id="70845-126">ジョブの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="70845-126">Gets job name.</span></span> <span data-ttu-id="70845-127">ARM リソース URI でジョブの識別子として使用されます。</span><span class="sxs-lookup"><span data-stu-id="70845-127">Used as job identifier in ARM resource URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>