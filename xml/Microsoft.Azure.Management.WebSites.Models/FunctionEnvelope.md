<Type Name="FunctionEnvelope" FullName="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope">
  <TypeSignature Language="C#" Value="public class FunctionEnvelope : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FunctionEnvelope extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope" />
  <TypeSignature Language="VB.NET" Value="Public Class FunctionEnvelope&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type FunctionEnvelope = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="55ec4-101">Web ジョブの情報です。</span><span class="sxs-lookup"><span data-stu-id="55ec4-101">Web Job Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionEnvelope ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-102">FunctionEnvelope クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-102">Initializes a new instance of the FunctionEnvelope class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionEnvelope (string id = null, string name = null, string kind = null, string type = null, string functionEnvelopeName = null, string functionAppId = null, string scriptRootPathHref = null, string scriptHref = null, string configHref = null, string secretsFileHref = null, string href = null, object config = null, System.Collections.Generic.IDictionary&lt;string,string&gt; files = null, string testData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string functionEnvelopeName, string functionAppId, string scriptRootPathHref, string scriptHref, string configHref, string secretsFileHref, string href, object config, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; files, string testData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional functionEnvelopeName As String = null, Optional functionAppId As String = null, Optional scriptRootPathHref As String = null, Optional scriptHref As String = null, Optional configHref As String = null, Optional secretsFileHref As String = null, Optional href As String = null, Optional config As Object = null, Optional files As IDictionary(Of String, String) = null, Optional testData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope : string * string * string * string * string * string * string * string * string * string * string * obj * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope" Usage="new Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope (id, name, kind, type, functionEnvelopeName, functionAppId, scriptRootPathHref, scriptHref, configHref, secretsFileHref, href, config, files, testData)" />
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
        <Parameter Name="functionEnvelopeName" Type="System.String" />
        <Parameter Name="functionAppId" Type="System.String" />
        <Parameter Name="scriptRootPathHref" Type="System.String" />
        <Parameter Name="scriptHref" Type="System.String" />
        <Parameter Name="configHref" Type="System.String" />
        <Parameter Name="secretsFileHref" Type="System.String" />
        <Parameter Name="href" Type="System.String" />
        <Parameter Name="config" Type="System.Object" />
        <Parameter Name="files" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="testData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="55ec4-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="55ec4-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="55ec4-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="55ec4-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="55ec4-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="55ec4-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="55ec4-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="55ec4-106">Resource type.</span></span></param>
        <param name="functionEnvelopeName"><span data-ttu-id="55ec4-107">関数名。</span><span class="sxs-lookup"><span data-stu-id="55ec4-107">Function name.</span></span></param>
        <param name="functionAppId"><span data-ttu-id="55ec4-108">関数アプリの id。</span><span class="sxs-lookup"><span data-stu-id="55ec4-108">Function App ID.</span></span></param>
        <param name="scriptRootPathHref"><span data-ttu-id="55ec4-109">ルート パス URI のスクリプトを作成します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-109">Script root path URI.</span></span></param>
        <param name="scriptHref"><span data-ttu-id="55ec4-110">スクリプト URI です。</span><span class="sxs-lookup"><span data-stu-id="55ec4-110">Script URI.</span></span></param>
        <param name="configHref"><span data-ttu-id="55ec4-111">構成の URI。</span><span class="sxs-lookup"><span data-stu-id="55ec4-111">Config URI.</span></span></param>
        <param name="secretsFileHref"><span data-ttu-id="55ec4-112">機密データ ファイルの URI。</span><span class="sxs-lookup"><span data-stu-id="55ec4-112">Secrets file URI.</span></span></param>
        <param name="href"><span data-ttu-id="55ec4-113">関数の URI。</span><span class="sxs-lookup"><span data-stu-id="55ec4-113">Function URI.</span></span></param>
        <param name="config"><span data-ttu-id="55ec4-114">構成情報。</span><span class="sxs-lookup"><span data-stu-id="55ec4-114">Config information.</span></span></param>
        <param name="files"><span data-ttu-id="55ec4-115">ファイルの一覧です。</span><span class="sxs-lookup"><span data-stu-id="55ec4-115">File list.</span></span></param>
        <param name="testData"><span data-ttu-id="55ec4-116">Azure ポータルを使用してテストするときに使用されるデータをテストします。</span><span class="sxs-lookup"><span data-stu-id="55ec4-116">Test data used when testing via the Azure Portal.</span></span></param>
        <summary>
            <span data-ttu-id="55ec4-117">FunctionEnvelope クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-117">Initializes a new instance of the FunctionEnvelope class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Config">
      <MemberSignature Language="C#" Value="public object Config { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Config" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.Config" />
      <MemberSignature Language="VB.NET" Value="Public Property Config As Object" />
      <MemberSignature Language="F#" Value="member this.Config : obj with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.Config" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.config")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-118">取得または設定情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-118">Gets or sets config information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigHref">
      <MemberSignature Language="C#" Value="public string ConfigHref { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigHref" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.ConfigHref" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigHref As String" />
      <MemberSignature Language="F#" Value="member this.ConfigHref : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.ConfigHref" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.configHref")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-119">取得または設定 URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-119">Gets or sets config URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Files : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-120">取得またはファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-120">Gets or sets file list.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FunctionAppId">
      <MemberSignature Language="C#" Value="public string FunctionAppId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FunctionAppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.FunctionAppId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FunctionAppId As String" />
      <MemberSignature Language="F#" Value="member this.FunctionAppId : string" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.FunctionAppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.functionAppId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-121">Gets 関数アプリ id。</span><span class="sxs-lookup"><span data-stu-id="55ec4-121">Gets function App ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FunctionEnvelopeName">
      <MemberSignature Language="C#" Value="public string FunctionEnvelopeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FunctionEnvelopeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.FunctionEnvelopeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FunctionEnvelopeName As String" />
      <MemberSignature Language="F#" Value="member this.FunctionEnvelopeName : string" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.FunctionEnvelopeName" />
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
            <span data-ttu-id="55ec4-122">関数名を取得します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-122">Gets function name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Href">
      <MemberSignature Language="C#" Value="public string Href { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Href" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.Href" />
      <MemberSignature Language="VB.NET" Value="Public Property Href As String" />
      <MemberSignature Language="F#" Value="member this.Href : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.Href" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.href")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-123">取得または関数の URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-123">Gets or sets function URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptHref">
      <MemberSignature Language="C#" Value="public string ScriptHref { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptHref" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.ScriptHref" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptHref As String" />
      <MemberSignature Language="F#" Value="member this.ScriptHref : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.ScriptHref" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scriptHref")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-124">取得またはスクリプト URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-124">Gets or sets script URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptRootPathHref">
      <MemberSignature Language="C#" Value="public string ScriptRootPathHref { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptRootPathHref" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.ScriptRootPathHref" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptRootPathHref As String" />
      <MemberSignature Language="F#" Value="member this.ScriptRootPathHref : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.ScriptRootPathHref" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scriptRootPathHref")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-125">取得またはスクリプトのルート パス URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-125">Gets or sets script root path URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretsFileHref">
      <MemberSignature Language="C#" Value="public string SecretsFileHref { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretsFileHref" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.SecretsFileHref" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretsFileHref As String" />
      <MemberSignature Language="F#" Value="member this.SecretsFileHref : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.SecretsFileHref" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secretsFileHref")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-126">取得またはシークレット ファイル URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-126">Gets or sets secrets file URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestData">
      <MemberSignature Language="C#" Value="public string TestData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TestData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.TestData" />
      <MemberSignature Language="VB.NET" Value="Public Property TestData As String" />
      <MemberSignature Language="F#" Value="member this.TestData : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.FunctionEnvelope.TestData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.testData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55ec4-127">取得または Azure ポータルを使用してテストするときに使用されるテスト データを設定します。</span><span class="sxs-lookup"><span data-stu-id="55ec4-127">Gets or sets test data used when testing via the Azure Portal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>