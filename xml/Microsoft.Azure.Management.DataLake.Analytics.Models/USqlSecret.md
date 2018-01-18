<Type Name="USqlSecret" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret">
  <TypeSignature Language="C#" Value="public class USqlSecret : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlSecret extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlSecret&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlSecret = class&#xA;    inherit CatalogItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f41dc-101">Data Lake Analytics カタログ U-SQL シークレット アイテムです。</span><span class="sxs-lookup"><span data-stu-id="f41dc-101">A Data Lake Analytics catalog U-SQL secret item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlSecret ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f41dc-102">USqlSecret クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f41dc-102">Initializes a new instance of the USqlSecret class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlSecret (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string name = null, Nullable&lt;DateTimeOffset&gt; creationTime = null, string uri = null, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string name, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; creationTime, string uri, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.Nullable{System.DateTimeOffset},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional name As String = null, Optional creationTime As Nullable(Of DateTimeOffset) = null, Optional uri As String = null, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret : string * Nullable&lt;Guid&gt; * string * string * Nullable&lt;DateTimeOffset&gt; * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret (computeAccountName, version, databaseName, name, creationTime, uri, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="f41dc-103">Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f41dc-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="f41dc-104">カタログ アイテムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="f41dc-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="f41dc-105">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f41dc-105">the name of the database.</span></span></param>
        <param name="name"><span data-ttu-id="f41dc-106">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="f41dc-106">the name of the secret.</span></span></param>
        <param name="creationTime"><span data-ttu-id="f41dc-107">資格情報オブジェクトの作成時間。</span><span class="sxs-lookup"><span data-stu-id="f41dc-107">the creation time of the credential object.</span></span> <span data-ttu-id="f41dc-108">これは、シークレットに関する GET から返される情報のみです。</span><span class="sxs-lookup"><span data-stu-id="f41dc-108">This is the only information returned about a secret from a GET.</span></span></param>
        <param name="uri"><span data-ttu-id="f41dc-109">形式で、シークレットの URI 識別子&lt;hostname&gt;:&lt;ポート&gt;</span><span class="sxs-lookup"><span data-stu-id="f41dc-109">the URI identifier for the secret in the format &lt;hostname&gt;:&lt;port&gt;</span></span></param>
        <param name="password"><span data-ttu-id="f41dc-110">渡すシークレットのパスワード</span><span class="sxs-lookup"><span data-stu-id="f41dc-110">the password for the secret to pass in</span></span></param>
        <summary>
            <span data-ttu-id="f41dc-111">USqlSecret クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f41dc-111">Initializes a new instance of the USqlSecret class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f41dc-112">取得または資格情報オブジェクトの作成時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="f41dc-112">Gets or sets the creation time of the credential object.</span></span> <span data-ttu-id="f41dc-113">これは、シークレットに関する GET から返される情報のみです。</span><span class="sxs-lookup"><span data-stu-id="f41dc-113">This is the only information returned about a secret from a GET.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f41dc-114">取得またはデータベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f41dc-114">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f41dc-115">取得またはシークレットの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f41dc-115">Gets or sets the name of the secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f41dc-116">取得または設定を渡すシークレットのパスワード</span><span class="sxs-lookup"><span data-stu-id="f41dc-116">Gets or sets the password for the secret to pass in</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public string Uri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.Uri" />
      <MemberSignature Language="VB.NET" Value="Public Property Uri As String" />
      <MemberSignature Language="F#" Value="member this.Uri : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f41dc-117">形式で、シークレットの URI 識別子の設定を取得または&amp;lt; のホスト名&amp;gt;:&amp;lt; port&amp;gt;</span><span class="sxs-lookup"><span data-stu-id="f41dc-117">Gets or sets the URI identifier for the secret in the format &amp;lt;hostname&amp;gt;:&amp;lt;port&amp;gt;</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>