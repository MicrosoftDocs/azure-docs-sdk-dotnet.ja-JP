<Type Name="UserDefinedFunction" FullName="Microsoft.Azure.Documents.UserDefinedFunction">
  <TypeSignature Language="C#" Value="public class UserDefinedFunction : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserDefinedFunction extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.UserDefinedFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class UserDefinedFunction&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type UserDefinedFunction = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="c20a2-101">ユーザーを表しますは、Azure Cosmos DB サービスで関数を定義します。</span><span class="sxs-lookup"><span data-stu-id="c20a2-101">Represents a user defined function in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="c20a2-102">Azure の Cosmos DB には、JavaScript ユーザー定義関数 (Udf) は、データベースに格納され、クエリ内で使用できますがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="c20a2-102">Azure Cosmos DB supports JavaScript user defined functions (UDFs) which are stored in the database and can be used inside queries.</span></span> <span data-ttu-id="c20a2-103">クエリで Udf を使用する方法について http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c20a2-103">Refer to http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration for how to use UDFs within queries.</span></span>
            <span data-ttu-id="c20a2-104">JavaScript での Udf の実装の詳細については http://azure.microsoft.com/documentation/articles/documentdb-programming/#udf を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c20a2-104">Refer to http://azure.microsoft.com/documentation/articles/documentdb-programming/#udf for more details about implementing UDFs in JavaScript.</span></span>
            </remarks>
    <example>
            <span data-ttu-id="c20a2-105">次の例では、登録および Udf を使用する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="c20a2-105">The following examples show how to register and use UDFs.</span></span>
            <code language="c#"><![CDATA[
            await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "calculateTax", Body = @"function(amt) { return amt * 0.05; }" });
            client.CreateDocumentQuery<Book>(collectionLink, "SELECT VALUE udf.calculateTax(b.price) FROM books b");
            client.CreateDocumentQuery<Book>(collectionLink, new SqlQuerySpec("SELECT VALUE udf.calculateTax(b.price) FROM books b"));
            client.CreateDocumentQuery<Book>(collectionLink).Select(b => UserDefinedFunctionProvider.Invoke("calculateTax", b.Price));
            
            await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "toLowerCase", Body = @"function(s) { return s.ToLowerCase(); }" });
            client.CreateDocumentQuery<Book>(collectionLink, "SELECT * FROM books b WHERE b.toLowerCase = 'war and peace'");
            client.CreateDocumentQuery<Book>(collectionLink, new SqlQuerySpec(
                "SELECT * FROM books b WHERE b.toLowerCase = @bookNameLowerCase",
                new SqlParameterCollection(new SqlParameter[] {new SqlParameter { Name = "@bookNameLowerCase", Value = "War And Peace".ToLower()
             }})));
             client.CreateDocumentQuery<Book>(collectionLink).Where(b => UserDefinedFunctionProvider.Invoke("toLowerCase", b.Title) == "war and peace");
             ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserDefinedFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.UserDefinedFunction.#ctor" />
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
            <span data-ttu-id="c20a2-106">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="c20a2-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.UserDefinedFunction.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.Documents.UserDefinedFunction.Body" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c20a2-107">取得または Azure Cosmos DB サービスのユーザー定義関数の本体を設定します。</span><span class="sxs-lookup"><span data-stu-id="c20a2-107">Gets or sets the body of the user defined function for the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="c20a2-108">ユーザーの本体は、関数を定義します。</span><span class="sxs-lookup"><span data-stu-id="c20a2-108">The body of the user defined function.</span></span></value>
        <remarks><span data-ttu-id="c20a2-109">これは、有効な JavaScript 関数の例:"function (入力) {戻り input.toLowerCase();}"でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="c20a2-109">This must be a valid JavaScript function e.g. "function (input) { return input.toLowerCase(); }".</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>