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
            Azure Cosmos DB アカウントにデータベースを表します。
            </summary>
    <remarks>
            各 Azure Cosmos DB データベース アカウントには、0 個以上のデータベースを持つことができます。 Azure Cosmos DB 内のデータベースは、ドキュメントのコレクションと、ユーザーの論理コンテナーです。
            参照してください<see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#databases</see>データベースの詳細についてはします。
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
    <example>
            次の例では、"MyDatabase"の Id プロパティを持つ、新しいデータベースを作成します。
            <code language="c#"><![CDATA[ 
            using (DocumentClient client = new DocumentClient(new Uri("service endpoint"), "auth key"))
            {
                Database db = await client.CreateDatabaseAsync(new Database { Id = "MyDatabase" });
            }
            ]]></code></example>
    <example> 
            次の例では、10000 に設定されて OfferThroughput をこのデータベース内でコレクションを作成します。
            <code language="c#"><![CDATA[
            DocumentCollection coll = await client.CreateDocumentCollectionAsync(db.SelfLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} );
            ]]></code></example>
    <example>
            クエリによって、SelfLink を取得する Id のデータベースの次の例です。
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            Database database = client.CreateDatabaseQuery().Where(d => d.Id == "MyDatabase").AsEnumerable().FirstOrDefault();
            string databaseLink = database.SelfLink;
            ]]></code></example>
    <example>
            次の例では、その SelfLink プロパティを使用してデータベースを削除します。
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Database" /> Azure Cosmos DB サービスのクラスです。
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
            Azure Cosmos DB サービスからコレクションの自己リンクを取得します。
            </summary>
        <value>
            自己リンクのコレクション データベースにします。
            </value>
        <remarks>
            すべての Azure Cosmos DB リソースが、変更できない静的アドレス指定可能な URI を保持します。 すると、; の形式でコレクションの場合/db db_rid/colls/db_rid がデータベースのリソース id の値を表します。リソース id はなくにして、作成時に、データベース内部で生成されたの不変 id です。
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
            Azure Cosmos DB サービスからのユーザーの自己リンクを取得します。
            </summary>
        <value>
            データベース内のユーザーに対しては自己リンクは、します。
            </value>
        <remarks>
            すべての Azure Cosmos DB リソースが、変更できない静的アドレス指定可能な URI を保持します。 ユーザーは、これにかかる; の形式/db db_rid/ユーザー/db_rid がデータベースのリソース id の値を表します。リソース id はなくにして、作成時に、データベース内部で生成されたの不変 id です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>