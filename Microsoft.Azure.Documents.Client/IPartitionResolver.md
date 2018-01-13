<Type Name="IPartitionResolver" FullName="Microsoft.Azure.Documents.Client.IPartitionResolver">
  <TypeSignature Language="C#" Value="public interface IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPartitionResolver" />
  <TypeSignature Language="F#" Value="type IPartitionResolver = interface" />
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
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            これは、データベースのパーティションのリゾルバーを表します。 パーティション キー、Azure Cosmos DB サービスのパーティション キーに一致するリンクのコレクションを返します。
            </summary>
    <remarks>
      <para>
            IPartitionResolver のサポートは廃止されました。 使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。
            </para>
      <para>
            DocumentClient を使用すると、作成し、データベースごとに IPartitionResolvers 実装を登録できます。 登録されると、コレクションではなくデータベースに対して直接ドキュメントの操作を行うことができます。 IPartitionResolvers には、ExtractPartitionKey、ResolveForCreate および ResolveForRead 3 つのメソッドがあります。
            </para>
      <para>
            LINQ クエリと ReadFeed 反復子を使用して、ResolveForRead 内部的には、要求のパーティション キーに一致するすべてのコレクションを反復処理します。 同様に、ルーティングする ResolveForCreate が右のパーティションに作成操作の使用を作成します。 置換のために必要な変更はありません、削除およびドキュメントを保持するコレクションへの参照が格納されているドキュメントを使用するための読み取り。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj" Usage="iPartitionResolver.GetPartitionKey document" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="document">ドキュメント オブジェクト。</param>
        <summary>
            Cosmos DB の Azure サービス内のドキュメントからパーティション キーを抽出します。
            </summary>
        <returns>ドキュメントのパーティション キーです。</returns>
        <remarks>
            一般的な実装は、ドキュメント (ユーザー ID など) から 1 つのプロパティの値を取得またはバージョン ID などの複合プロパティを抽出デバイス #) またはに基づいて、ドキュメントの種類の例: カスタム ロジックを実装して、ユーザーの id の値を抽出するが、userMessages の userId を抽出します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string" Usage="iPartitionResolver.ResolveForCreate partitionKey" />
      <MemberType>Method</MemberType>
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
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">評価対象を決定するために使用するパーティション キーのコレクションは、操作を作成します。</param>
        <summary>
            パーティション キーを指定するには、このコレクションを返します Cosmos DB の Azure サービスでドキュメントを作成するための自己リンクします。
            </summary>
        <returns>指定されたパーティション キーでドキュメントを作成するコレクションに対しては自己リンクは、します。</returns>
        <remarks>
            戻り値は、有効なコレクションの自己リンク文字列、書式 db/db_rid/colls/col_rid をする必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="iPartitionResolver.ResolveForRead partitionKey" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">読み取り、つまり、クエリまたは読み取りフィードのターゲット コレクションを決定するために使用するパーティション キーです。</param>
        <summary>
            指定されたパーティション キーが返されます。 コレクションの一覧は、自己からの読み取りにリンクします。
            </summary>
        <returns>指定されたパーティション キーの読み取り要求を実行するには、コレクションの自己リンクします。</returns>
        <remarks>
            戻り値は、形式 db/db_rid/colls/col_rid 内のコレクションの自己リンクした文字列の IEnumerable をする必要があります。
            異なり ResolveForCreate、これは 1: n 異なるコレクションに時間の経過と共に作成される 1 つのパーティション キーとして、または Azure Cosmos DB サービスのコレクションの間のパーティション キーのデータ移行を実行しているためです。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>