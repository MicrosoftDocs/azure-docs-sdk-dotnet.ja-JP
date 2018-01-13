<Type Name="Database" FullName="Microsoft.Azure.Documents.Database">
  <TypeSignature Language="C#" Value="public class Database : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Database extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Database" />
  <TypeSignature Language="VB.NET" Value="Public Class Database&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Database = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4daea-101">Azure Cosmos DB アカウントにデータベースを表します。</span><span class="sxs-lookup"><span data-stu-id="4daea-101">Represents a database in the Azure Cosmos DB account.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="4daea-102">各 Azure Cosmos DB データベース アカウントには、0 個以上のデータベースを持つことができます。</span><span class="sxs-lookup"><span data-stu-id="4daea-102">Each Azure Cosmos DB database account can have zero or more databases.</span></span> <span data-ttu-id="4daea-103">Azure Cosmos DB 内のデータベースは、ドキュメントのコレクションと、ユーザーの論理コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="4daea-103">A database in Azure Cosmos DB is a logical container for document collections and users.</span></span>
            <span data-ttu-id="4daea-104">参照してください<see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#databases</see>データベースの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="4daea-104">Refer to <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#databases</see> for more details on databases.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
    <example>
            <span data-ttu-id="4daea-105">次の例では、"MyDatabase"の Id プロパティを持つ、新しいデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="4daea-105">The example below creates a new Database with an Id property of 'MyDatabase'.</span></span>
            <code language="c#"><![CDATA[ 
            using (DocumentClient client = new DocumentClient(new Uri("service endpoint"), "auth key"))
            {
                Database db = await client.CreateDatabaseAsync(new Database { Id = "MyDatabase" });
            }
            ]]></code></example>
    <example> 
            <span data-ttu-id="4daea-106">次の例では、10000 に設定されて OfferThroughput をこのデータベース内でコレクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="4daea-106">The example below creates a collection within this database with OfferThroughput set to 10000.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection coll = await client.CreateDocumentCollectionAsync(db.SelfLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} );
            ]]></code></example>
    <example>
            <span data-ttu-id="4daea-107">クエリによって、SelfLink を取得する Id のデータベースの次の例です。</span><span class="sxs-lookup"><span data-stu-id="4daea-107">The example below queries for a Database by Id to retrieve the SelfLink.</span></span>
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            Database database = client.CreateDatabaseQuery().Where(d => d.Id == "MyDatabase").AsEnumerable().FirstOrDefault();
            string databaseLink = database.SelfLink;
            ]]></code></example>
    <example>
            <span data-ttu-id="4daea-108">次の例では、その SelfLink プロパティを使用してデータベースを削除します。</span><span class="sxs-lookup"><span data-stu-id="4daea-108">The example below deletes the database using its SelfLink property.</span></span>
            <code language="c#"><![CDATA[
            await client.DeleteDatabaseAsync(db.SelfLink);
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Database ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Database.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4daea-109">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Database" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="4daea-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Database" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionsLink">
      <MemberSignature Language="C#" Value="public string CollectionsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Database.CollectionsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionsLink As String" />
      <MemberSignature Language="F#" Value="member this.CollectionsLink : string" Usage="Microsoft.Azure.Documents.Database.CollectionsLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_colls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4daea-110">Azure Cosmos DB サービスからコレクションの自己リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="4daea-110">Gets the self-link for collections from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4daea-111">自己リンクのコレクション データベースにします。</span><span class="sxs-lookup"><span data-stu-id="4daea-111">The self-link for collections in the database.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="4daea-112">すべての Azure Cosmos DB リソースが、変更できない静的アドレス指定可能な URI を保持します。</span><span class="sxs-lookup"><span data-stu-id="4daea-112">Every Azure Cosmos DB resource has a static, immutable, addressable URI.</span></span> <span data-ttu-id="4daea-113">すると、; の形式でコレクションの場合/db db_rid/colls/db_rid がデータベースのリソース id の値を表します。リソース id はなくにして、作成時に、データベース内部で生成されたの不変 id です。</span><span class="sxs-lookup"><span data-stu-id="4daea-113">For collections, this takes the form of; /dbs/db_rid/colls/ where db_rid represents the value of the database's resource id. A resource id is not the id given to a database on creation, but an internally generated immutable id.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsersLink">
      <MemberSignature Language="C#" Value="public string UsersLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Database.UsersLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsersLink As String" />
      <MemberSignature Language="F#" Value="member this.UsersLink : string" Usage="Microsoft.Azure.Documents.Database.UsersLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_users")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4daea-114">Azure Cosmos DB サービスからのユーザーの自己リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="4daea-114">Gets the self-link for users from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4daea-115">データベース内のユーザーに対しては自己リンクは、します。</span><span class="sxs-lookup"><span data-stu-id="4daea-115">The self-link for users in the database.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="4daea-116">すべての Azure Cosmos DB リソースが、変更できない静的アドレス指定可能な URI を保持します。</span><span class="sxs-lookup"><span data-stu-id="4daea-116">Every Azure Cosmos DB resource has a static, immutable, addressable URI.</span></span> <span data-ttu-id="4daea-117">ユーザーは、これにかかる; の形式/db db_rid/ユーザー/db_rid がデータベースのリソース id の値を表します。リソース id はなくにして、作成時に、データベース内部で生成されたの不変 id です。</span><span class="sxs-lookup"><span data-stu-id="4daea-117">For users, this takes the form of; /dbs/db_rid/users/ where db_rid represents the value of the database's resource id. A resource id is not the id given to a database on creation, but an internally generated immutable id.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>