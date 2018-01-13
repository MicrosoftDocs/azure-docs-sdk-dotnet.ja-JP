<Type Name="ResourceResponse&lt;TResource&gt;" FullName="Microsoft.Azure.Documents.Client.ResourceResponse&lt;TResource&gt;">
  <TypeSignature Language="C#" Value="public class ResourceResponse&lt;TResource&gt; : Microsoft.Azure.Documents.Client.ResourceResponseBase, Microsoft.Azure.Documents.Client.IResourceResponse&lt;TResource&gt; where TResource : Resourcenew()" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceResponse`1&lt;.ctor (class Microsoft.Azure.Documents.Resource) TResource&gt; extends Microsoft.Azure.Documents.Client.ResourceResponseBase implements class Microsoft.Azure.Documents.Client.IResourceResponse`1&lt;!TResource&gt;, class Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceResponse(Of TResource)&#xA;Inherits ResourceResponseBase&#xA;Implements IResourceResponse(Of TResource)" />
  <TypeSignature Language="F#" Value="type ResourceResponse&lt;'Resource (requires 'Resource :&gt; Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; = class&#xA;    inherit ResourceResponseBase&#xA;    interface IResourceResponse&lt;'Resource (requires 'Resource :&gt; Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;&#xA;    interface IResourceResponseBase" />
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
    <TypeParameter Name="TResource">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Client.ResourceResponseBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IResourceResponse&lt;TResource&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TResource">リソースの種類。</typeparam>
    <summary>
            Cosmos DB の Azure サービス内の 1 つのオブジェクトを返すメソッドで使用されるテンプレート クラスを表します。
            </summary>
    <remarks>
            すべての応答を作成、読み取り、更新し、ResourceResponse オブジェクトでラップされた応答を Azure Cosmos DB リソースの戻り値の削除します。 これには、アクティビティの ID とリソースの使用量のクォータ要求単位 (RequestCharge) を含む Azure Cosmos DB の呼び出しからの応答ヘッダーからのメタデータが含まれています。
            </remarks>
    <altmember cref="P:Microsoft.Azure.Documents.Client.ResourceResponse`1.Resource" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.FeedResponse`1" />
    <example>
            次の例は、使用される要求単位、アクティビティの ID と CreateDocumentAsync 呼び出しから StatusCode を抽出します。
            <code language="c#"><![CDATA[
            ResourceResponse<Document> response = await client.CreateDocumentAsync(collectionLink, document);
            Console.WriteLine(response.RequestCharge);
            Console.WriteLine(response.ActivityId); 
            Console.WriteLine(response.StatusCode); // HttpStatusCode.Created or 201
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ResourceResponse`1.#ctor" />
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
            Azure Cosmos DB サービスの目的をモックに公開されているコンス トラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceResponse (TResource resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!TResource resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ResourceResponse`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (resource As TResource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; : 'Resource -&gt; Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;" Usage="new Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; resource" />
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
        <Parameter Name="resource" Type="TResource" />
      </Parameters>
      <Docs>
        <param name="resource"></param>
        <summary>
            Azure Cosmos DB サービスの目的をモックに公開されているコンス トラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator TResource (Microsoft.Azure.Documents.Client.ResourceResponse&lt;TResource&gt; source);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname !TResource op_Implicit(class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;!TResource&gt; source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ResourceResponse`1.op_Implicit(Microsoft.Azure.Documents.Client.ResourceResponse{`0})~`0" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (source As ResourceResponse(Of TResource)) As TResource" />
      <MemberSignature Language="F#" Value="static member op_Implicit : Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; -&gt; 'Resource" Usage="Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;.op_Implicit source" />
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
        <ReturnType>TResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Documents.Client.ResourceResponse&lt;TResource&gt;" />
      </Parameters>
      <Docs>
        <param name="source">ResourceResponse ソースです。</param>
        <summary>
            暗黙的に Azure Cosmos DB サービスからの応答でリソースを返します。
            </summary>
        <returns>リソース オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public TResource Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TResource Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponse`1.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As TResource" />
      <MemberSignature Language="F#" Value="member this.Resource : 'Resource" Usage="Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;.Resource" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponse`1.Resource</InterfaceMember>
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
        <ReturnType>TResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスからの応答で返されるリソースを取得します。
            </summary>
        <value>
            リソースは、応答で返されます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>