<Type Name="ServerInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner">
  <TypeSignature Language="C#" Value="public class ServerInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ServerInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2ec9c-101">Azure SQL サーバーを表します。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-101">Represents an Azure SQL server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ec9c-102">ServerInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-102">Initializes a new instance of the ServerInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string fullyQualifiedDomainName = null, string version = null, string administratorLogin = null, string administratorLoginPassword = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string fullyQualifiedDomainName, string version, string administratorLogin, string administratorLoginPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional fullyQualifiedDomainName As String = null, Optional version As String = null, Optional administratorLogin As String = null, Optional administratorLoginPassword As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner (location, id, name, type, tags, fullyQualifiedDomainName, version, administratorLogin, administratorLoginPassword)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="fullyQualifiedDomainName" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="administratorLogin" Type="System.String" />
        <Parameter Name="administratorLoginPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="fullyQualifiedDomainName"><span data-ttu-id="2ec9c-103">サーバーの完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-103">The fully qualified domain name of the server.</span></span></param>
        <param name="version"><span data-ttu-id="2ec9c-104">サーバーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-104">The version of the server.</span></span> <span data-ttu-id="2ec9c-105">使用可能な値が含まれます: '2.0'、'12.0'</span><span class="sxs-lookup"><span data-stu-id="2ec9c-105">Possible values include: '2.0', '12.0'</span></span></param>
        <param name="administratorLogin"><span data-ttu-id="2ec9c-106">サーバーの管理者ユーザー名。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-106">Administrator username for the server.</span></span> <span data-ttu-id="2ec9c-107">のみ指定できますと、サーバーが作成される (の作成が必要)。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-107">Can only be specified when the server is being created (and is required for creation).</span></span></param>
        <param name="administratorLoginPassword"><span data-ttu-id="2ec9c-108">(サーバーの作成に必要) の管理者ログイン パスワード。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-108">The administrator login password (required for server creation).</span></span></param>
        <summary>
            <span data-ttu-id="2ec9c-109">ServerInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-109">Initializes a new instance of the ServerInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLogin">
      <MemberSignature Language="C#" Value="public string AdministratorLogin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLogin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.AdministratorLogin" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLogin As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLogin : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.AdministratorLogin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2ec9c-110">取得またはサーバーの管理者のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-110">Gets or sets administrator username for the server.</span></span> <span data-ttu-id="2ec9c-111">のみ指定できますと、サーバーが作成される (の作成が必要)。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-111">Can only be specified when the server is being created (and is required for creation).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdministratorLoginPassword">
      <MemberSignature Language="C#" Value="public string AdministratorLoginPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorLoginPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.AdministratorLoginPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdministratorLoginPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorLoginPassword : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.AdministratorLoginPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2ec9c-112">取得または管理者 (サーバーの作成に必要) ログイン パスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-112">Gets or sets the administrator login password (required for server creation).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullyQualifiedDomainName">
      <MemberSignature Language="C#" Value="public string FullyQualifiedDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FullyQualifiedDomainName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.FullyQualifiedDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FullyQualifiedDomainName As String" />
      <MemberSignature Language="F#" Value="member this.FullyQualifiedDomainName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.FullyQualifiedDomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2ec9c-113">サーバーの完全修飾ドメイン名を取得します。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-113">Gets the fully qualified domain name of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2ec9c-114">取得またはサーバーのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="2ec9c-114">Gets or sets the version of the server.</span></span> <span data-ttu-id="2ec9c-115">使用可能な値が含まれます: '2.0'、'12.0'</span><span class="sxs-lookup"><span data-stu-id="2ec9c-115">Possible values include: '2.0', '12.0'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>