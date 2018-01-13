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
            <span data-ttu-id="9387b-101">Azure Cosmos DB サービス DocumentClient インスタンスで使用するには、さまざまな Uri の作成を支援するヘルパー クラスが必要です。</span><span class="sxs-lookup"><span data-stu-id="9387b-101">Helper class to assist in creating the various Uris needed for use with the DocumentClient instance in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <example>
            <span data-ttu-id="9387b-102">次の例では、UriFactory を使用して、DocumentCollectionLink を作成しを使用して、されるドキュメントを作成します。</span><span class="sxs-lookup"><span data-stu-id="9387b-102">The example below uses UriFactory to create a DocumentCollectionLink and then uses that to create a Document.</span></span>
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
        <param name="databaseId"><span data-ttu-id="9387b-103">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-103">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-104">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-104">The collection id</span></span></param>
        <param name="documentId"><span data-ttu-id="9387b-105">ドキュメント id</span><span class="sxs-lookup"><span data-stu-id="9387b-105">The document id</span></span></param>
        <param name="attachmentId"><span data-ttu-id="9387b-106">添付ファイルの id</span><span class="sxs-lookup"><span data-stu-id="9387b-106">The attachment id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-107">データベース、コレクション、ドキュメント、および添付ファイルの id を指定するには、添付ファイル リンクが作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-107">Given a database, collection, document, and attachment id, this creates an attachment link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-108">/Dbs/{0} colls/の形式での添付ファイル リンク \ <paramref name="databaseId" />/docs/\ {2 \} の添付ファイル/\ {3\} {0} エスケープ Uri のバージョンの中の<paramref name="databaseId" />、{1} される<paramref name="collectionId" />、{2} されている、 <paramref name="documentId" /> {3} され<paramref name="attachmentId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-108">An attachment link in the format of /dbs/{0}/colls/{1}/docs/{2}/attachments/{3} with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" />, {2} being the <paramref name="documentId" /> and {3} being <paramref name="attachmentId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-109">置換、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Attachment" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-109">Would be used when replacing, or deleting an <see cref="T:Microsoft.Azure.Documents.Attachment" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-110">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-110">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-111">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-111">The collection id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-112">データベースとコレクションの id を指定するには、コレクションのリンクを作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-112">Given a database and collection id, this creates a collection link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-113">/Dbs/{0} colls/の形式でコレクションのリンク \ <paramref name="databaseId" />/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" /> {1} され<paramref name="collectionId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-113">A collection link in the format of /dbs/{0}/colls/{1}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="collectionId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-114">更新または削除時に使用される、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />、作成、 <see cref="T:Microsoft.Azure.Documents.Document" />、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />、 <see cref="T:Microsoft.Azure.Documents.Trigger" />、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />、または Azure Cosmos db CreateDocumentQuery でクエリを実行するときにします。</span><span class="sxs-lookup"><span data-stu-id="9387b-114">Would be used when updating or deleting a <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, creating a <see cref="T:Microsoft.Azure.Documents.Document" />, a <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, a <see cref="T:Microsoft.Azure.Documents.Trigger" />, a <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, or when executing a query with CreateDocumentQuery in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-115">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-115">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-116">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-116">The collection id</span></span></param>
        <param name="conflictId"><span data-ttu-id="9387b-117">競合 id</span><span class="sxs-lookup"><span data-stu-id="9387b-117">The conflict id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-118">データベース、コレクションとの競合 id が指定された、競合のリンク作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-118">Given a database, collection and conflict id, this creates a conflict link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-119">/Dbs/{0} colls/の形式での競合リンク \ <paramref name="databaseId" />/競合/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="conflictId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-119">A conflict link in the format of /dbs/{0}/colls/{1}/conflicts/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="conflictId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-120">作成するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Conflict" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-120">Would be used when creating a <see cref="T:Microsoft.Azure.Documents.Conflict" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-121">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-121">The database id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-122">データベース id を指定するには、データベースのリンクを作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-122">Given a database id, this creates a database link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-123">データベースのリンクの/dbs/{0}/{0} される Uri の形式でエスケープのバージョン、<paramref name="databaseId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-123">A database link in the format of /dbs/{0}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-124">作成または削除するときに使用される、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />または<see cref="T:Microsoft.Azure.Documents.User" />Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-124">Would be used when creating or deleting a <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> or a <see cref="T:Microsoft.Azure.Documents.User" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-125">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-125">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-126">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-126">The collection id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-127">データベースとコレクションの id を指定するには、コレクションのリンクを作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-127">Given a database and collection id, this creates a collection link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-128">/Dbs/{0} colls/の形式でコレクションのリンク \ <paramref name="databaseId" />/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" /> {1} され<paramref name="collectionId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-128">A collection link in the format of /dbs/{0}/colls/{1}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="collectionId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-129">更新または削除時に使用される、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />、作成、 <see cref="T:Microsoft.Azure.Documents.Document" />、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />、 <see cref="T:Microsoft.Azure.Documents.Trigger" />、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />、または Azure Cosmos db CreateDocumentQuery でクエリを実行するときにします。</span><span class="sxs-lookup"><span data-stu-id="9387b-129">Would be used when updating or deleting a <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, creating a <see cref="T:Microsoft.Azure.Documents.Document" />, a <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, a <see cref="T:Microsoft.Azure.Documents.Trigger" />, a <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, or when executing a query with CreateDocumentQuery in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-130">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-130">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-131">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-131">The collection id</span></span></param>
        <param name="documentId"><span data-ttu-id="9387b-132">ドキュメント id</span><span class="sxs-lookup"><span data-stu-id="9387b-132">The document id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-133">データベース、コレクションおよびドキュメントの id を指定するには、ドキュメントのリンク作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-133">Given a database, collection and document id, this creates a document link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-134">/Dbs/{0} colls/の形式でドキュメントのリンク \ <paramref name="databaseId" />/docs/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="documentId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-134">A document link in the format of /dbs/{0}/colls/{1}/docs/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="documentId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-135">作成するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Attachment" />、または置換または削除すると、 <see cref="T:Microsoft.Azure.Documents.Document" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-135">Would be used when creating an <see cref="T:Microsoft.Azure.Documents.Attachment" />, or when replacing or deleting a <see cref="T:Microsoft.Azure.Documents.Document" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-136">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-136">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-137">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-137">The collection id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-138">データベースとコレクションを指定するには、このリンクを作成パーティション キーの範囲 Cosmos DB の Azure サービスにします。</span><span class="sxs-lookup"><span data-stu-id="9387b-138">Given a database and collection, this creates a partition key ranges link in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-139">パーティション キーの範囲は/dbs/{0} colls/の形式でリンク \ <paramref name="databaseId" /> pkranges {0} される Uri のエスケープのバージョン/、 <paramref name="databaseId" /> {1} され<paramref name="collectionId" />です。</span><span class="sxs-lookup"><span data-stu-id="9387b-139">A partition key ranges link in the format of /dbs/{0}/colls/{1}/pkranges with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="collectionId" />.</span></span>
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
        <param name="databaseId"><span data-ttu-id="9387b-140">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-140">The database id</span></span></param>
        <param name="userId"><span data-ttu-id="9387b-141">ユーザー id</span><span class="sxs-lookup"><span data-stu-id="9387b-141">The user id</span></span></param>
        <param name="permissionId"><span data-ttu-id="9387b-142">アクセス許可 id</span><span class="sxs-lookup"><span data-stu-id="9387b-142">The permission id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-143">データベースとユーザー id を指定するには、アクセス許可のリンクを作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-143">Given a database and user id, this creates a permission link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-144">/Dbs/{0}/ユーザー/の形式のアクセス許可のリンク \ <paramref name="databaseId" />/アクセス許可/\ {2 \} {0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="userId" />{2} され<paramref name="permissionId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-144">A permission link in the format of /dbs/{0}/users/{1}/permissions/{2} with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="userId" /> and {2} being <paramref name="permissionId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-145">置換または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Permission" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-145">Would be used when replacing or deleting a <see cref="T:Microsoft.Azure.Documents.Permission" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-146">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-146">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-147">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-147">The collection id</span></span></param>
        <param name="storedProcedureId"><span data-ttu-id="9387b-148">ストアド プロシージャの id</span><span class="sxs-lookup"><span data-stu-id="9387b-148">The stored procedure id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-149">データベース、コレクション、およびストアド プロシージャの id を指定するには、ストアド プロシージャのリンク作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-149">Given a database, collection and stored proc id, this creates a stored proc link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-150">/Dbs/{0} colls/の形式でのストアド プロシージャ リンク \ <paramref name="databaseId" />/ストアド プロシージャ/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="storedProcedureId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-150">A stored procedure link in the format of /dbs/{0}/colls/{1}/sprocs/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="storedProcedureId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-151">交換、実行、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-151">Would be used when replacing, executing, or deleting a <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-152">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-152">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-153">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-153">The collection id</span></span></param>
        <param name="triggerId"><span data-ttu-id="9387b-154">トリガーの id</span><span class="sxs-lookup"><span data-stu-id="9387b-154">The trigger id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-155">データベース、コレクション、およびトリガーの id を指定するには、トリガーのリンク作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-155">Given a database, collection and trigger id, this creates a trigger link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-156">/Dbs/{0} colls/の形式でトリガー リンク \ <paramref name="databaseId" />/トリガー/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="triggerId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-156">A trigger link in the format of /dbs/{0}/colls/{1}/triggers/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="triggerId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-157">交換、実行、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Trigger" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-157">Would be used when replacing, executing, or deleting a <see cref="T:Microsoft.Azure.Documents.Trigger" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-158">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-158">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="9387b-159">コレクション id</span><span class="sxs-lookup"><span data-stu-id="9387b-159">The collection id</span></span></param>
        <param name="udfId"><span data-ttu-id="9387b-160">Udf id</span><span class="sxs-lookup"><span data-stu-id="9387b-160">The udf id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-161">データベース、コレクションおよび udf の id を指定するには、udf のリンク作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-161">Given a database, collection and udf id, this creates a udf link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-162">/Dbs/{0} colls/の形式での udf リンク \ <paramref name="databaseId" />/udf/\ {2 \}/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" />、{1} される<paramref name="collectionId" />{2} され、<paramref name="udfId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-162">A udf link in the format of /dbs/{0}/colls/{1}/udfs/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="udfId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-163">交換、実行、または削除するときに使用される、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-163">Would be used when replacing, executing, or deleting a <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> in Azure Cosmos DB.</span></span></remarks>
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
        <param name="databaseId"><span data-ttu-id="9387b-164">データベースの id</span><span class="sxs-lookup"><span data-stu-id="9387b-164">The database id</span></span></param>
        <param name="userId"><span data-ttu-id="9387b-165">ユーザー id</span><span class="sxs-lookup"><span data-stu-id="9387b-165">The user id</span></span></param>
        <summary>
            <span data-ttu-id="9387b-166">データベースとユーザー id を指定するには、ユーザーのリンクを作成されます。</span><span class="sxs-lookup"><span data-stu-id="9387b-166">Given a database and user id, this creates a user link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9387b-167">/Dbs/{0}/ユーザー/の形式でユーザー リンク \ <paramref name="databaseId" />/{0} エスケープ Uri のバージョンの中で、 <paramref name="databaseId" /> {1} され<paramref name="userId" /></span><span class="sxs-lookup"><span data-stu-id="9387b-167">A user link in the format of /dbs/{0}/users/{1}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="userId" /></span></span></returns>
        <remarks><span data-ttu-id="9387b-168">作成するときに使用される、 <see cref="T:Microsoft.Azure.Documents.Permission" />、または置換または削除すると、 <see cref="T:Microsoft.Azure.Documents.User" /> Azure Cosmos DB にします。</span><span class="sxs-lookup"><span data-stu-id="9387b-168">Would be used when creating a <see cref="T:Microsoft.Azure.Documents.Permission" />, or when replacing or deleting a <see cref="T:Microsoft.Azure.Documents.User" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
  </Members>
</Type>