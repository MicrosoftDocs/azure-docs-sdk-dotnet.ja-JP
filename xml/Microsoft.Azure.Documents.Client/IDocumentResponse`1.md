<Type Name="IDocumentResponse&lt;TDocument&gt;" FullName="Microsoft.Azure.Documents.Client.IDocumentResponse&lt;TDocument&gt;">
  <TypeSignature Language="C#" Value="public interface IDocumentResponse&lt;TDocument&gt; : Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentResponse`1&lt;TDocument&gt; implements class Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IDocumentResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentResponse(Of TDocument)&#xA;Implements IResourceResponseBase" />
  <TypeSignature Language="F#" Value="type IDocumentResponse&lt;'Document&gt; = interface&#xA;    interface IResourceResponseBase" />
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
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IResourceResponseBase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TDocument">To be added.</typeparam>
    <summary>
            <span data-ttu-id="cf1e1-101">Azure Cosmos DB サービスの目的をモックに公開されるインターフェイス。</span><span class="sxs-lookup"><span data-stu-id="cf1e1-101">Interface exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Document">
      <MemberSignature Language="C#" Value="public TDocument Document { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TDocument Document" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IDocumentResponse`1.Document" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Document As TDocument" />
      <MemberSignature Language="F#" Value="member this.Document : 'Document" Usage="Microsoft.Azure.Documents.Client.IDocumentResponse&lt;'Document&gt;.Document" />
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
        <ReturnType>TDocument</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf1e1-102">応答で返されたドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="cf1e1-102">Gets the document returned in the response.</span></span>
            </summary>
        <value>
            <span data-ttu-id="cf1e1-103">応答で返されるドキュメント。</span><span class="sxs-lookup"><span data-stu-id="cf1e1-103">The document returned in the response.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="cf1e1-104">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="cf1e1-104">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>