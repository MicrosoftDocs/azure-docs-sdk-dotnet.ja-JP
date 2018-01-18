<Type Name="Server" FullName="Microsoft.Azure.Management.Sql.Models.Server">
  <TypeSignature Language="C#" Value="public class Server : Microsoft.Azure.Management.Sql.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Server extends Microsoft.Azure.Management.Sql.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.Server" />
  <TypeSignature Language="VB.NET" Value="Public Class Server&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type Server = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e022d-101">Azure SQL データベース サーバーの場合。</span><span class="sxs-lookup"><span data-stu-id="e022d-101">An Azure SQL Database server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Server ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Server.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e022d-102">サーバー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e022d-102">Initializes a new instance of the Server class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Server (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Sql.Models.ResourceIdentity identity = null, string kind = null, string administratorLogin = null, string administratorLoginPassword = null, string version = null, string state = null, string fullyQualifiedDomainName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Sql.Models.ResourceIdentity identity, string kind, string administratorLogin, string administratorLoginPassword, string version, string state, string fullyQualifiedDomainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Server.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Sql.Models.ResourceIdentity,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional identity As ResourceIdentity = null, Optional kind As String = null, Optional administratorLogin As String = null, Optional administratorLoginPassword As String = null, Optional version As String = null, Optional state As String = null, Optional fullyQualifiedDomainName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.Server : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Sql.Models.ResourceIdentity * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="new Microsoft.Azure.Management.Sql.Models.Server (location, id, name, type, tags, identity, kind, administratorLogin, administratorLoginPassword, version, state, fullyQualifiedDomainName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Sql.Models.ResourceIdentity" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="administratorLogin" Type="System.String" />
        <Parameter Name="administratorLoginPassword" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="fullyQualifiedDomainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="e022d-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="e022d-103">Resource location.</span></span></param>
        <param name="id"><span data-ttu-id="e022d-104">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="e022d-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="e022d-105">リソース名。</span><span class="sxs-lookup"><span data-stu-id="e022d-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="e022d-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="e022d-106">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="e022d-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="e022d-107">Resource tags.</span></span></param>
        <param name="identity"><span data-ttu-id="e022d-108">サーバーの Azure Active Directory id。</span><span class="sxs-lookup"><span data-stu-id="e022d-108">The Azure Active Directory identity of the server.</span></span></param>
        <param name="kind"><span data-ttu-id="e022d-109">Sql server の種類。</span><span class="sxs-lookup"><span data-stu-id="e022d-109">Kind of sql server.</span></span> <span data-ttu-id="e022d-110">これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。</span><span class="sxs-lookup"><span data-stu-id="e022d-110">This is metadata used for the Azure portal experience.</span></span></param>
        <param name="administratorLogin"><span data-ttu-id="e022d-111">サーバーの管理者ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="e022d-111">Administrator username for the server.</span></span> <span data-ttu-id="e022d-112">作成後は変更できません。</span><span class="sxs-lookup"><span data-stu-id="e022d-112">Once created it cannot be changed.</span></span></param>
        <param name="administratorLoginPassword"><span data-ttu-id="e022d-113">(サーバーの作成に必要) の管理者ログイン パスワード。</span><span class="sxs-lookup"><span data-stu-id="e022d-113">The administrator login password (required for server creation).</span></span></param>
        <param name="version"><span data-ttu-id="e022d-114">サーバーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="e022d-114">The version of the server.</span></span></param>
        <param name="state"><span data-ttu-id="e022d-115">サーバーの状態。</span><span class="sxs-lookup"><span data-stu-id="e022d-115">The state of the server.</span></span></param>
        <param name="fullyQualifiedDomainName"><span data-ttu-id="e022d-116">サーバーの完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="e022d-116">The fully qualified domain name of the server.</span></span></param>
        <summary>
            <span data-ttu-id="e022d-117">サーバー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e022d-117">Initializes a new instance of the Server class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLogin">
      <MemberSignature Language="C#" Value="public string AdministratorLogin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLogin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Server.AdministratorLogin" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLogin As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLogin : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Server.AdministratorLogin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.administratorLogin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e022d-118">取得またはサーバーの管理者のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="e022d-118">Gets or sets administrator username for the server.</span></span> <span data-ttu-id="e022d-119">作成後は変更できません。</span><span class="sxs-lookup"><span data-stu-id="e022d-119">Once created it cannot be changed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLoginPassword">
      <MemberSignature Language="C#" Value="public string AdministratorLoginPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLoginPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Server.AdministratorLoginPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLoginPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLoginPassword : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Server.AdministratorLoginPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.administratorLoginPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e022d-120">取得または管理者 (サーバーの作成に必要) ログイン パスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="e022d-120">Gets or sets the administrator login password (required for server creation).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullyQualifiedDomainName">
      <MemberSignature Language="C#" Value="public string FullyQualifiedDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FullyQualifiedDomainName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Server.FullyQualifiedDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FullyQualifiedDomainName As String" />
      <MemberSignature Language="F#" Value="member this.FullyQualifiedDomainName : string" Usage="Microsoft.Azure.Management.Sql.Models.Server.FullyQualifiedDomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fullyQualifiedDomainName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e022d-121">サーバーの完全修飾ドメイン名を取得します。</span><span class="sxs-lookup"><span data-stu-id="e022d-121">Gets the fully qualified domain name of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.ResourceIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.ResourceIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Server.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As ResourceIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Sql.Models.ResourceIdentity with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Server.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ResourceIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e022d-122">取得またはサーバーの Azure Active Directory id を設定します。</span><span class="sxs-lookup"><span data-stu-id="e022d-122">Gets or sets the Azure Active Directory identity of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Server.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.Server.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e022d-123">Sql server の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="e022d-123">Gets kind of sql server.</span></span> <span data-ttu-id="e022d-124">これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。</span><span class="sxs-lookup"><span data-stu-id="e022d-124">This is metadata used for the Azure portal experience.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Server.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.Server.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e022d-125">サーバーの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e022d-125">Gets the state of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Server.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="server.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e022d-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e022d-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e022d-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e022d-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Server.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Server.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e022d-128">取得またはサーバーのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="e022d-128">Gets or sets the version of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>