<Type Name="DocumentResponse&lt;TDocument&gt;" FullName="Microsoft.Azure.Documents.Client.DocumentResponse&lt;TDocument&gt;">
  <TypeSignature Language="C#" Value="public sealed class DocumentResponse&lt;TDocument&gt; : Microsoft.Azure.Documents.Client.ResourceResponseBase, Microsoft.Azure.Documents.Client.IDocumentResponse&lt;TDocument&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DocumentResponse`1&lt;TDocument&gt; extends Microsoft.Azure.Documents.Client.ResourceResponseBase implements class Microsoft.Azure.Documents.Client.IDocumentResponse`1&lt;!TDocument&gt;, class Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.DocumentResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DocumentResponse(Of TDocument)&#xA;Inherits ResourceResponseBase&#xA;Implements IDocumentResponse(Of TDocument)" />
  <TypeSignature Language="F#" Value="type DocumentResponse&lt;'Document&gt; = class&#xA;    inherit ResourceResponseBase&#xA;    interface IDocumentResponse&lt;'Document&gt;&#xA;    interface IResourceResponseBase" />
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
  <TypeParameters>
    <TypeParameter Name="TDocument" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Client.ResourceResponseBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IDocumentResponse&lt;TDocument&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TDocument"><span data-ttu-id="b402a-101">ドキュメントの種類。</span><span class="sxs-lookup"><span data-stu-id="b402a-101">the document type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="b402a-102">Cosmos DB の Azure サービス内の 1 つのオブジェクトを返すメソッドで使用されるテンプレート クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="b402a-102">Represents the template class used by methods returning single objects in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="b402a-103">特定の型からの応答は、resource(ReadDocumentAsync{TDocument}) DocumentResponse オブジェクトでラップされた応答が返すドキュメントの読み取り。</span><span class="sxs-lookup"><span data-stu-id="b402a-103">Response from type-specific read of Document resource(ReadDocumentAsync{TDocument}) returns the response wrapped in a DocumentResponse object.</span></span> <span data-ttu-id="b402a-104">これには、アクティビティの ID、リソースの使用量のクォータと型指定されたドキュメント object(TDocument) 要求単位 (RequestCharge) を含む Azure Cosmos DB の呼び出しからの応答ヘッダーからのメタデータが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b402a-104">This contains the metadata from the response headers from the Azure Cosmos DB call including the request units (RequestCharge), activity ID, quotas/usage of resources and the typed document object(TDocument).</span></span>
            </remarks>
    <example>
            <span data-ttu-id="b402a-105">アクティビティの ID と StatusCode ReadDocumentAsync {顧客} の呼び出しに使用される、単位を要求する次の例が CustomerName プロパティを抽出します。</span><span class="sxs-lookup"><span data-stu-id="b402a-105">The following example extracts the CustomerName property, request units consumed, activity ID and StatusCode from a ReadDocumentAsync{Customer} call.</span></span>
            <code language="c#"><![CDATA[
            DocumentResponse<Customer> response = await client.ReadDocumentAsync<Customer>(documentLink);
            Console.WriteLine(response.Document.CustomerName);
            Console.WriteLine(response.RequestCharge);
            Console.WriteLine(response.ActivityId); 
            Console.WriteLine(response.StatusCode); // HttpStatusCode.Created or 201
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.DocumentResponse`1.#ctor" />
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
            <span data-ttu-id="b402a-106">Azure Cosmos DB サービスの目的をモックに公開されているコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="b402a-106">Constructor exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentResponse (TDocument document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!TDocument document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.DocumentResponse`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (document As TDocument)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Client.DocumentResponse&lt;'Document&gt; : 'Document -&gt; Microsoft.Azure.Documents.Client.DocumentResponse&lt;'Document&gt;" Usage="new Microsoft.Azure.Documents.Client.DocumentResponse&lt;'Document&gt; document" />
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
      <Parameters>
        <Parameter Name="document" Type="TDocument" />
      </Parameters>
      <Docs>
        <param name="document"></param>
        <summary>
            <span data-ttu-id="b402a-107">Azure Cosmos DB サービスの目的をモックに公開されているコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="b402a-107">Constructor exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Document">
      <MemberSignature Language="C#" Value="public TDocument Document { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TDocument Document" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.DocumentResponse`1.Document" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Document As TDocument" />
      <MemberSignature Language="F#" Value="member this.Document : 'Document" Usage="Microsoft.Azure.Documents.Client.DocumentResponse&lt;'Document&gt;.Document" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IDocumentResponse`1.Document</InterfaceMember>
      </Implements>
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
        <ReturnType>TDocument</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b402a-108">Azure Cosmos DB サービスからの応答で返されたドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="b402a-108">Gets the document returned in the response from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b402a-109">応答で返されるドキュメント。</span><span class="sxs-lookup"><span data-stu-id="b402a-109">The document returned in the response.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator TDocument (Microsoft.Azure.Documents.Client.DocumentResponse&lt;TDocument&gt; source);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname !TDocument op_Implicit(class Microsoft.Azure.Documents.Client.DocumentResponse`1&lt;!TDocument&gt; source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.DocumentResponse`1.op_Implicit(Microsoft.Azure.Documents.Client.DocumentResponse{`0})~`0" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (source As DocumentResponse(Of TDocument)) As TDocument" />
      <MemberSignature Language="F#" Value="static member op_Implicit : Microsoft.Azure.Documents.Client.DocumentResponse&lt;'Document&gt; -&gt; 'Document" Usage="Microsoft.Azure.Documents.Client.DocumentResponse&lt;'Document&gt;.op_Implicit source" />
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
        <ReturnType>TDocument</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Documents.Client.DocumentResponse&lt;TDocument&gt;" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="b402a-110">DocumentResponse ソースです。</span><span class="sxs-lookup"><span data-stu-id="b402a-110">The DocumentResponse source.</span></span></param>
        <summary>
            <span data-ttu-id="b402a-111">暗黙的に Azure Cosmos DB サービスからの応答では、ドキュメントを返します。</span><span class="sxs-lookup"><span data-stu-id="b402a-111">Returns the document in the response implicitly from the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="b402a-112">ドキュメント オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b402a-112">The document object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>