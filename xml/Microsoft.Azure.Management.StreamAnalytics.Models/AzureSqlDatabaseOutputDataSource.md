<Type Name="AzureSqlDatabaseOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource">
  <TypeSignature Language="C#" Value="public class AzureSqlDatabaseOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlDatabaseOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlDatabaseOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type AzureSqlDatabaseOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Sql/Server/Database")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1f938-101">Azure SQL データベースの出力のデータ ソースをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="1f938-101">Describes an Azure SQL database output data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlDatabaseOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1f938-102">AzureSqlDatabaseOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1f938-102">Initializes a new instance of the AzureSqlDatabaseOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlDatabaseOutputDataSource (string server = null, string database = null, string user = null, string password = null, string table = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string server, string database, string user, string password, string table) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional server As String = null, Optional database As String = null, Optional user As String = null, Optional password As String = null, Optional table As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource : string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource (server, database, user, password, table)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="1f938-103">Azure SQL データベースを含む SQL server の名前。</span><span class="sxs-lookup"><span data-stu-id="1f938-103">The name of the SQL server containing the Azure SQL database.</span></span> <span data-ttu-id="1f938-104">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="database"><span data-ttu-id="1f938-105">Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="1f938-105">The name of the Azure SQL database.</span></span> <span data-ttu-id="1f938-106">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="user"><span data-ttu-id="1f938-107">Azure SQL データベースへの接続に使用されるユーザー名。</span><span class="sxs-lookup"><span data-stu-id="1f938-107">The user name that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="1f938-108">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="password"><span data-ttu-id="1f938-109">Azure SQL データベースへの接続に使用されるパスワードです。</span><span class="sxs-lookup"><span data-stu-id="1f938-109">The password that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="1f938-110">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-110">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="table"><span data-ttu-id="1f938-111">Azure SQL データベース内のテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="1f938-111">The name of the table in the Azure SQL database.</span></span> <span data-ttu-id="1f938-112">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-112">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <summary>
            <span data-ttu-id="1f938-113">AzureSqlDatabaseOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1f938-113">Initializes a new instance of the AzureSqlDatabaseOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public string Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As String" />
      <MemberSignature Language="F#" Value="member this.Database : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Database" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.database")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1f938-114">取得または Azure SQL データベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1f938-114">Gets or sets the name of the Azure SQL database.</span></span> <span data-ttu-id="1f938-115">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-115">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1f938-116">取得または Azure SQL データベースへの接続に使用されるパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="1f938-116">Gets or sets the password that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="1f938-117">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-117">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public string Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As String" />
      <MemberSignature Language="F#" Value="member this.Server : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Server" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.server")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1f938-118">取得または Azure SQL データベースを含む SQL server の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1f938-118">Gets or sets the name of the SQL server containing the Azure SQL database.</span></span> <span data-ttu-id="1f938-119">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-119">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Table" />
      <MemberSignature Language="VB.NET" Value="Public Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1f938-120">取得または Azure SQL データベースのテーブルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1f938-120">Gets or sets the name of the table in the Azure SQL database.</span></span>
            <span data-ttu-id="1f938-121">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-121">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="User">
      <MemberSignature Language="C#" Value="public string User { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string User" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.User" />
      <MemberSignature Language="VB.NET" Value="Public Property User As String" />
      <MemberSignature Language="F#" Value="member this.User : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseOutputDataSource.User" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.user")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1f938-122">取得または Azure SQL データベースへの接続に使用されるユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="1f938-122">Gets or sets the user name that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="1f938-123">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="1f938-123">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>