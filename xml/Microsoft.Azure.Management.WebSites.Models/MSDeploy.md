<Type Name="MSDeploy" FullName="Microsoft.Azure.Management.WebSites.Models.MSDeploy">
  <TypeSignature Language="C#" Value="public class MSDeploy : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MSDeploy extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MSDeploy" />
  <TypeSignature Language="VB.NET" Value="Public Class MSDeploy&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type MSDeploy = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="592c8-101">MSDeploy ARM 配置情報</span><span class="sxs-lookup"><span data-stu-id="592c8-101">MSDeploy ARM PUT information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeploy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeploy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="592c8-102">MSDeploy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="592c8-102">Initializes a new instance of the MSDeploy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeploy (string id = null, string name = null, string kind = null, string type = null, string packageUri = null, string connectionString = null, string dbType = null, string setParametersXmlFileUri = null, System.Collections.Generic.IDictionary&lt;string,string&gt; setParameters = null, Nullable&lt;bool&gt; skipAppData = null, Nullable&lt;bool&gt; appOffline = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string packageUri, string connectionString, string dbType, string setParametersXmlFileUri, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; setParameters, valuetype System.Nullable`1&lt;bool&gt; skipAppData, valuetype System.Nullable`1&lt;bool&gt; appOffline) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeploy.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional packageUri As String = null, Optional connectionString As String = null, Optional dbType As String = null, Optional setParametersXmlFileUri As String = null, Optional setParameters As IDictionary(Of String, String) = null, Optional skipAppData As Nullable(Of Boolean) = null, Optional appOffline As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MSDeploy : string * string * string * string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.MSDeploy" Usage="new Microsoft.Azure.Management.WebSites.Models.MSDeploy (id, name, kind, type, packageUri, connectionString, dbType, setParametersXmlFileUri, setParameters, skipAppData, appOffline)" />
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
        <Parameter Name="packageUri" Type="System.String" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="dbType" Type="System.String" />
        <Parameter Name="setParametersXmlFileUri" Type="System.String" />
        <Parameter Name="setParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="skipAppData" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="appOffline" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="592c8-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="592c8-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="592c8-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="592c8-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="592c8-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="592c8-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="592c8-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="592c8-106">Resource type.</span></span></param>
        <param name="packageUri"><span data-ttu-id="592c8-107">パッケージ URI</span><span class="sxs-lookup"><span data-stu-id="592c8-107">Package URI</span></span></param>
        <param name="connectionString"><span data-ttu-id="592c8-108">SQL 接続文字列</span><span class="sxs-lookup"><span data-stu-id="592c8-108">SQL Connection String</span></span></param>
        <param name="dbType"><span data-ttu-id="592c8-109">データベースの種類</span><span class="sxs-lookup"><span data-stu-id="592c8-109">Database Type</span></span></param>
        <param name="setParametersXmlFileUri"><span data-ttu-id="592c8-110">URI の MSDeploy パラメーター ファイル。</span><span class="sxs-lookup"><span data-stu-id="592c8-110">URI of MSDeploy Parameters file.</span></span> <span data-ttu-id="592c8-111">設定しないでください SetParameters を使用する場合。</span><span class="sxs-lookup"><span data-stu-id="592c8-111">Must not be set if SetParameters is used.</span></span></param>
        <param name="setParameters"><span data-ttu-id="592c8-112">MSDeploy パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="592c8-112">MSDeploy Parameters.</span></span> <span data-ttu-id="592c8-113">設定しないでください SetParametersXmlFileUri を使用する場合。</span><span class="sxs-lookup"><span data-stu-id="592c8-113">Must not be set if SetParametersXmlFileUri is used.</span></span></param>
        <param name="skipAppData"><span data-ttu-id="592c8-114">MSDeploy 操作で、App_Data ディレクトリはスキップするかどうかを制御します。</span><span class="sxs-lookup"><span data-stu-id="592c8-114">Controls whether the MSDeploy operation skips the App_Data directory.</span></span>
            <span data-ttu-id="592c8-115">場合設定&lt;コード&gt;true&lt;/code&gt;先に既存の App_Data ディレクトリは削除されません、およびソース内の任意の App_Data ディレクトリは無視されます。</span><span class="sxs-lookup"><span data-stu-id="592c8-115">If set to &lt;code&gt;true&lt;/code&gt;, the existing App_Data directory on the destination will not be deleted, and any App_Data directory in the source will be ignored.</span></span>
            <span data-ttu-id="592c8-116">設定は&lt;コード&gt;false&lt;/code&gt;既定です。</span><span class="sxs-lookup"><span data-stu-id="592c8-116">Setting is &lt;code&gt;false&lt;/code&gt; by default.</span></span></param>
        <param name="appOffline"><span data-ttu-id="592c8-117">MSDeploy 操作を実行しながら、AppOffline ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="592c8-117">Sets the AppOffline rule while the MSDeploy operation executes.</span></span>
            <span data-ttu-id="592c8-118">設定は&lt;コード&gt;false&lt;/code&gt;既定です。</span><span class="sxs-lookup"><span data-stu-id="592c8-118">Setting is &lt;code&gt;false&lt;/code&gt; by default.</span></span></param>
        <summary>
            <span data-ttu-id="592c8-119">MSDeploy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="592c8-119">Initializes a new instance of the MSDeploy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppOffline">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AppOffline { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AppOffline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeploy.AppOffline" />
      <MemberSignature Language="VB.NET" Value="Public Property AppOffline As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AppOffline : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeploy.AppOffline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appOffline")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="592c8-120">取得または設定 MSDeploy 操作を実行しながら、AppOffline ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="592c8-120">Gets or sets sets the AppOffline rule while the MSDeploy operation executes.</span></span>
            <span data-ttu-id="592c8-121">設定は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt; 既定でします。</span><span class="sxs-lookup"><span data-stu-id="592c8-121">Setting is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt; by default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeploy.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeploy.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="592c8-122">取得または SQL 接続文字列を設定</span><span class="sxs-lookup"><span data-stu-id="592c8-122">Gets or sets SQL Connection String</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DbType">
      <MemberSignature Language="C#" Value="public string DbType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DbType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeploy.DbType" />
      <MemberSignature Language="VB.NET" Value="Public Property DbType As String" />
      <MemberSignature Language="F#" Value="member this.DbType : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeploy.DbType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dbType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="592c8-123">取得またはデータベースの種類の設定</span><span class="sxs-lookup"><span data-stu-id="592c8-123">Gets or sets database Type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PackageUri">
      <MemberSignature Language="C#" Value="public string PackageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PackageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeploy.PackageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property PackageUri As String" />
      <MemberSignature Language="F#" Value="member this.PackageUri : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeploy.PackageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.packageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="592c8-124">取得またはパッケージ URI を設定</span><span class="sxs-lookup"><span data-stu-id="592c8-124">Gets or sets package URI</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; SetParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; SetParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeploy.SetParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property SetParameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.SetParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeploy.SetParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.setParameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="592c8-125">取得または mSDeploy パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="592c8-125">Gets or sets mSDeploy Parameters.</span></span> <span data-ttu-id="592c8-126">設定しないでください SetParametersXmlFileUri を使用する場合。</span><span class="sxs-lookup"><span data-stu-id="592c8-126">Must not be set if SetParametersXmlFileUri is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetParametersXmlFileUri">
      <MemberSignature Language="C#" Value="public string SetParametersXmlFileUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SetParametersXmlFileUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeploy.SetParametersXmlFileUri" />
      <MemberSignature Language="VB.NET" Value="Public Property SetParametersXmlFileUri As String" />
      <MemberSignature Language="F#" Value="member this.SetParametersXmlFileUri : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeploy.SetParametersXmlFileUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.setParametersXmlFileUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="592c8-127">取得または URI の MSDeploy パラメーター ファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="592c8-127">Gets or sets URI of MSDeploy Parameters file.</span></span> <span data-ttu-id="592c8-128">設定しないでください SetParameters を使用する場合。</span><span class="sxs-lookup"><span data-stu-id="592c8-128">Must not be set if SetParameters is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipAppData">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SkipAppData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SkipAppData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeploy.SkipAppData" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipAppData As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SkipAppData : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeploy.SkipAppData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.skipAppData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="592c8-129">取得または MSDeploy 操作は、App_Data ディレクトリをスキップするかどうか、コントロールを設定します。</span><span class="sxs-lookup"><span data-stu-id="592c8-129">Gets or sets controls whether the MSDeploy operation skips the App_Data directory.</span></span>
            <span data-ttu-id="592c8-130">場合に設定&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt;、先にディレクトリを削除できませんが、既存の app_data フォルダーと、ソース内の任意の App_Data ディレクトリは無視されます。</span><span class="sxs-lookup"><span data-stu-id="592c8-130">If set to &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, the existing App_Data directory on the destination will not be deleted, and any App_Data directory in the source will be ignored.</span></span>
            <span data-ttu-id="592c8-131">設定は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt; 既定でします。</span><span class="sxs-lookup"><span data-stu-id="592c8-131">Setting is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt; by default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>