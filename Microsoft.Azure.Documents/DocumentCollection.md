<Type Name="DocumentCollection" FullName="Microsoft.Azure.Documents.DocumentCollection">
  <TypeSignature Language="C#" Value="public class DocumentCollection : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentCollection extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.DocumentCollection" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentCollection&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DocumentCollection = class&#xA;    inherit Resource" />
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
            Cosmos DB の Azure サービスでドキュメントのコレクションを表します。 コレクションは、ドキュメントの名前付きの論理コンテナーです。 
            </summary>
    <remarks>
            データベースは、0 個以上の名前付きコレクションを含めることがあり、0 個以上の JSON ドキュメントの各コレクションで構成されます。 スキーマ フリーである同じ構造またはフィールドを共有するコレクション内のドキュメントは必要ありません。 コレクションは、アプリケーションのリソースにあるため、承認できます、マスター _ キーまたはリソース キーを使用します。
            参照してください<see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#collections</see>コレクションの詳細についてはします。
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.IndexingPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
    <altmember cref="T:Microsoft.Azure.Documents.Document" />
    <altmember cref="T:Microsoft.Azure.Documents.Database" />
    <altmember cref="T:Microsoft.Azure.Documents.Offer" />
    <example>
            次の例では、50000 単位あたりの要求のスループットを新しいパーティションのコレクションを作成します。
            パーティション キーは、このコレクション内のすべてのドキュメントに最初のレベル '国' プロパティです。
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection 
                { 
                    Id = "MyCollection",
                    PartitionKey = new PartitionKeyDefinition
                    {
                        Paths = new Collection<string> { "/country" }
                    }
                }, 
                new RequestOptions { OfferThroughput = 50000} ).Result;
            ]]></code></example>
    <example>
            次の例では、10000 に設定されて OfferThroughput を新しいコレクションを作成します。
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} ).Result;
            ]]></code></example>
    <example>
            次の例では、カスタム インデックス作成ポリシーを使用して新しいコレクションを作成します。
            <code language="c#"><![CDATA[
            DocumentCollection collectionSpec = new DocumentCollection { Id ="MyCollection" };
            collectionSpec.IndexingPolicy.Automatic = true;
            collectionSpec.IndexingPolicy.IndexingMode = IndexingMode.Consistent;
            collection = await client.CreateDocumentCollectionAsync(database.SelfLink, collectionSpec);
            ]]></code></example>
    <example>
            次の例では、Book という種類のこのコレクション内のドキュメントを作成します。
            <code language="c#"><![CDATA[
            Document doc = await client.CreateDocumentAsync(collection.SelfLink, new Book { Title = "War and Peace" });
            ]]></code></example>
    <example>
            クエリによって、SelfLink を取得する Id のデータベースの次の例です。
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            DocumentCollection collection = client.CreateDocumentCollectionQuery(databaseLink).Where(c => c.Id == "myColl").AsEnumerable().FirstOrDefault();
            string collectionLink = collection.SelfLink;
            ]]></code></example>
    <example>
            次の例では、このコレクションを削除します。
            <code language="c#"><![CDATA[
            await client.DeleteDocumentCollectionAsync(collection.SelfLink);
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.DocumentCollection.#ctor" />
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConflictsLink">
      <MemberSignature Language="C#" Value="public string ConflictsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConflictsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConflictsLink As String" />
      <MemberSignature Language="F#" Value="member this.ConflictsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
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
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからコレクション内の競合の自己リンクを取得します。
            </summary>
        <value>
            自己リンクのコレクション内の競合をします。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultTimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultTimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="defaultTtl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからコレクション内のドキュメントを秒単位で有効期限の既定の時間を取得します。
            </summary>
        <value>
            これは、省略可能なプロパティです。
            有効な値はどちらかは 0 以外。 正の整数である必要があります '-1'、または<c>null</c>です。
            既定では、DefaultTimeToLive はコレクションの有効期限が無効になって null の意味に設定されます。
            測定単位は秒です。 最大値は 2147483647 です。
            </value>
        <remarks>
          <para>
            <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />有効期間の既定のポリシーとして、コレクション内のすべてのドキュメントに適用されます。
            個々 のドキュメントは設定して、既定の有効期限ポリシーを上書きする可能性があります、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />です。
            </para>
          <para>
            ときに、<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />は<c>null</c>に期限が無効にするコレクション。
            すべてのドキュメントが決して期限切れになります。 個々 のドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />無視されます。
            </para>
          <para>
            ときに、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> '-1' に期限がオンにするコレクションのです。
            既定では、すべてのドキュメントが決して期限切れです。 個々 のドキュメントことがある特定の有効期間の値を設定してその<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />です。 ドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />されますが、有効であるし、バック グラウンドで期限切れのドキュメントは削除されます。
            </para>
          <para>
            ときに、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> 0 以外の正の整数に期限がオンにするコレクションのです。
            有効期限 (秒) で、既定値は、すべてのドキュメントに適用されます。 ドキュメントが期限切れで、指定した後<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />後、その最終書き込み時刻の秒の値。
            個々 のドキュメントは設定して、既定の有効期限ポリシーを上書きする可能性があります、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />です。
            参照してください、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />詳細については、ドキュメントの最終的な有効期間ポリシーを評価します。
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Document" />
        <example>
            有効期間を無効にコレクションの次の例です。
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = null;
            ]]></code></example>
        <example>
            次の例を有効にする-有効期限コレクション。 既定では、すべてのドキュメント有効期限はありません。
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = -1;
            ]]></code></example>
        <example>
            次の例を有効にする-有効期限コレクション。 既定では、ドキュメントの有効期限 1000 秒後にその最終書き込み時刻以降。
            <code language="c#"><![CDATA[
            collection.DefaultTimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="DocumentsLink">
      <MemberSignature Language="C#" Value="public string DocumentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentsLink As String" />
      <MemberSignature Language="F#" Value="member this.DocumentsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_docs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからコレクション内のドキュメントの自己リンクを取得します。
            </summary>
        <value>
            コレクション内のドキュメントについては自己リンクは、します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingPolicy As IndexingPolicy" />
      <MemberSignature Language="F#" Value="member this.IndexingPolicy : Microsoft.Azure.Documents.IndexingPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
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
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" /> Cosmos DB の Azure サービスから、コレクションに関連付けられています。 
            </summary>
        <value>
            コレクションに関連付けられているインデックス作成ポリシー。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKeyDefinition" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKeyDefinition with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKeyDefinition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定<see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />Cosmos DB の Azure サービス内のオブジェクト。
            </summary>
        <value>
          <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> オブジェクト。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresLink">
      <MemberSignature Language="C#" Value="public string StoredProceduresLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoredProceduresLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresLink As String" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_sprocs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからコレクション内のストアド プロシージャの自己リンクを取得します。
            </summary>
        <value>
            コレクション内のストアド プロシージャには自己リンクは、します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersLink">
      <MemberSignature Language="C#" Value="public string TriggersLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersLink As String" />
      <MemberSignature Language="F#" Value="member this.TriggersLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
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
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからコレクション内のトリガーの自己リンクを取得します。
            </summary>
        <value>
            コレクション内のトリガーは自己リンクは、します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueKeyPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UniqueKeyPolicy As UniqueKeyPolicy" />
      <MemberSignature Language="F#" Value="member this.UniqueKeyPolicy : Microsoft.Azure.Documents.UniqueKeyPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uniqueKeyPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.UniqueKeyPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" /> Azure Cosmos DB サービスのコレクション内のドキュメントの一意性を保証します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsLink">
      <MemberSignature Language="C#" Value="public string UserDefinedFunctionsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserDefinedFunctionsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsLink As String" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
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
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ユーザーの自己リンクを取得には、Azure Cosmos DB サービスからコレクション内の関数が定義されています。
            </summary>
        <value>
            コレクションで関数を定義するユーザーの自己リンクします。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>