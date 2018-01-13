<Type Name="UriFactory" FullName="Microsoft.Azure.Documents.Client.UriFactory">
  <TypeSignature Language="C#" Value="public static class UriFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UriFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.UriFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class UriFactory" />
  <TypeSignature Language="F#" Value="type UriFactory = class" />
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
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure Cosmos DB サービス DocumentClient インスタンスで使用するには、さまざまな Uri の作成を支援するヘルパー クラスが必要です。
            </summary>
    <remarks>To be added.</remarks>
    <example>
            次の例では、UriFactory を使用して、DocumentCollectionLink を作成しを使用して、されるドキュメントを作成します。
            <code language="c#"><![CDATA[ 
            Uri collUri = UriFactory.CreateDocumentCollectionUri("MyDb", "MyCollection");
            var doc = await client.CreateDocumentAsync(collUri, new {id = "MyDoc"});
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName="CreateAttachmentUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAttachmentUri (string databaseId, string collectionId, string documentId, string attachmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAttachmentUri(string databaseId, string collectionId, string documentId, string attachmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateAttachmentUri(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAttachmentUri (databaseId As String, collectionId As String, documentId As String, attachmentId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAttachmentUri : string * string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateAttachmentUri (databaseId, collectionId, documentId, attachmentId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
        <Parameter Name="attachmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <param name="documentId">ドキュメント id</param>
        <param name="attachmentId">添付ファイルの id</param>
        <summary>
            データベース、コレクション、ドキュメント、および添付ファイルの id を指定するには、添付ファイル リンクが作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式での添付ファイル リンク \ <paramref name="databaseId" />/docs/\ {2 \} の添付ファイル/\ {3\} {0} エスケープ Uri のバージョンの中の<paramref name="databaseId" />、{1} される<paramref name="collectionId" />、{2} されている、 <paramref name="documentId" /> {3} され<paramref name="attachmentId" /></returns>
        <remarks>置換、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Attachment" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateCollectionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateCollectionUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateCollectionUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateCollectionUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateCollectionUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateCollectionUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateCollectionUri (databaseId, collectionId)" />
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
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("CreateCollectionUri method is deprecated, please use CreateDocumentCollectionUri method instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <summary>
            データベースとコレクションの id を指定するには、コレクションのリンクを作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式でコレクションのリンク \ <paramref name="databaseId" />/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" /> {1} され<paramref name="collectionId" /></returns>
        <remarks>更新または削除時に使用される、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />、作成、 <see cref="T:Microsoft.Azure.Documents.Document" />、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />、 <see cref="T:Microsoft.Azure.Documents.Trigger" />、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />、または Azure Cosmos db CreateDocumentQuery でクエリを実行するときにします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateConflictUri">
      <MemberSignature Language="C#" Value="public static Uri CreateConflictUri (string databaseId, string collectionId, string conflictId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateConflictUri(string databaseId, string collectionId, string conflictId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateConflictUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateConflictUri (databaseId As String, collectionId As String, conflictId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateConflictUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateConflictUri (databaseId, collectionId, conflictId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="conflictId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <param name="conflictId">競合 id</param>
        <summary>
            データベース、コレクションとの競合 id が指定された、競合のリンク作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式での競合リンク \ <paramref name="databaseId" />/競合/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="conflictId" /></returns>
        <remarks>作成するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Conflict" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDatabaseUri (string databaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDatabaseUri(string databaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDatabaseUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDatabaseUri (databaseId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDatabaseUri : string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDatabaseUri databaseId" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <summary>
            データベース id を指定するには、データベースのリンクを作成されます。
            </summary>
        <returns>
            データベースのリンクの/dbs/{0}/{0} される Uri の形式でエスケープのバージョン、<paramref name="databaseId" /></returns>
        <remarks>作成または削除するときに使用される、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />または<see cref="T:Microsoft.Azure.Documents.User" />Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDocumentCollectionUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDocumentCollectionUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentCollectionUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDocumentCollectionUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDocumentCollectionUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentCollectionUri (databaseId, collectionId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <summary>
            データベースとコレクションの id を指定するには、コレクションのリンクを作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式でコレクションのリンク \ <paramref name="databaseId" />/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" /> {1} され<paramref name="collectionId" /></returns>
        <remarks>更新または削除時に使用される、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />、作成、 <see cref="T:Microsoft.Azure.Documents.Document" />、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />、 <see cref="T:Microsoft.Azure.Documents.Trigger" />、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />、または Azure Cosmos db CreateDocumentQuery でクエリを実行するときにします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDocumentUri (string databaseId, string collectionId, string documentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDocumentUri(string databaseId, string collectionId, string documentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDocumentUri (databaseId As String, collectionId As String, documentId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDocumentUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentUri (databaseId, collectionId, documentId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <param name="documentId">ドキュメント id</param>
        <summary>
            データベース、コレクションおよびドキュメントの id を指定するには、ドキュメントのリンク作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式でドキュメントのリンク \ <paramref name="databaseId" />/docs/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="documentId" /></returns>
        <remarks>作成するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Attachment" />、または置換または削除すると、 <see cref="T:Microsoft.Azure.Documents.Document" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionKeyRangesUri">
      <MemberSignature Language="C#" Value="public static Uri CreatePartitionKeyRangesUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreatePartitionKeyRangesUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreatePartitionKeyRangesUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreatePartitionKeyRangesUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreatePartitionKeyRangesUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreatePartitionKeyRangesUri (databaseId, collectionId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <summary>
            データベースとコレクションを指定するには、このリンクを作成パーティション キーの範囲 Cosmos DB の Azure サービスにします。
            </summary>
        <returns>
            パーティション キーの範囲は/dbs/{0} colls/の形式でリンク \ <paramref name="databaseId" /> pkranges {0} される Uri のエスケープのバージョン/、 <paramref name="databaseId" /> {1} され<paramref name="collectionId" />です。
            </returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionUri">
      <MemberSignature Language="C#" Value="public static Uri CreatePermissionUri (string databaseId, string userId, string permissionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreatePermissionUri(string databaseId, string userId, string permissionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreatePermissionUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreatePermissionUri (databaseId As String, userId As String, permissionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreatePermissionUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreatePermissionUri (databaseId, userId, permissionId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="permissionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="userId">ユーザー id</param>
        <param name="permissionId">アクセス許可 id</param>
        <summary>
            データベースとユーザー id を指定するには、アクセス許可のリンクを作成されます。
            </summary>
        <returns>
            /Dbs/{0}/ユーザー/の形式のアクセス許可のリンク \ <paramref name="databaseId" />/アクセス許可/\ {2 \} {0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="userId" />{2} され<paramref name="permissionId" /></returns>
        <remarks>置換または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Permission" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureUri">
      <MemberSignature Language="C#" Value="public static Uri CreateStoredProcedureUri (string databaseId, string collectionId, string storedProcedureId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateStoredProcedureUri(string databaseId, string collectionId, string storedProcedureId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateStoredProcedureUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateStoredProcedureUri (databaseId As String, collectionId As String, storedProcedureId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateStoredProcedureUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateStoredProcedureUri (databaseId, collectionId, storedProcedureId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="storedProcedureId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <param name="storedProcedureId">ストアド プロシージャの id</param>
        <summary>
            データベース、コレクション、およびストアド プロシージャの id を指定するには、ストアド プロシージャのリンク作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式でのストアド プロシージャ リンク \ <paramref name="databaseId" />/ストアド プロシージャ/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="storedProcedureId" /></returns>
        <remarks>交換、実行、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerUri">
      <MemberSignature Language="C#" Value="public static Uri CreateTriggerUri (string databaseId, string collectionId, string triggerId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateTriggerUri(string databaseId, string collectionId, string triggerId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateTriggerUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateTriggerUri (databaseId As String, collectionId As String, triggerId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateTriggerUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateTriggerUri (databaseId, collectionId, triggerId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="triggerId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <param name="triggerId">トリガーの id</param>
        <summary>
            データベース、コレクション、およびトリガーの id を指定するには、トリガーのリンク作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式でトリガー リンク \ <paramref name="databaseId" />/トリガー/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="triggerId" /></returns>
        <remarks>交換、実行、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Trigger" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateUserDefinedFunctionUri (string databaseId, string collectionId, string udfId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateUserDefinedFunctionUri(string databaseId, string collectionId, string udfId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateUserDefinedFunctionUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUserDefinedFunctionUri (databaseId As String, collectionId As String, udfId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateUserDefinedFunctionUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateUserDefinedFunctionUri (databaseId, collectionId, udfId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="udfId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="collectionId">コレクション id</param>
        <param name="udfId">Udf id</param>
        <summary>
            データベース、コレクションおよび udf の id を指定するには、udf のリンク作成されます。
            </summary>
        <returns>
            /Dbs/{0} colls/の形式での udf リンク \ <paramref name="databaseId" />/udf/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="udfId" /></returns>
        <remarks>交換、実行、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateUserUri">
      <MemberSignature Language="C#" Value="public static Uri CreateUserUri (string databaseId, string userId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateUserUri(string databaseId, string userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateUserUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUserUri (databaseId As String, userId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateUserUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateUserUri (databaseId, userId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">データベースの id</param>
        <param name="userId">ユーザー id</param>
        <summary>
            データベースとユーザー id を指定するには、ユーザーのリンクを作成されます。
            </summary>
        <returns>
            /Dbs/{0}/ユーザー/の形式でユーザー リンク \ <paramref name="databaseId" />/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" /> {1} され<paramref name="userId" /></returns>
        <remarks>作成するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Permission" />、または置換または削除すると、 <see cref="T:Microsoft.Azure.Documents.User" /> Azure Cosmos DB にします。</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
  </Members>
</Type>