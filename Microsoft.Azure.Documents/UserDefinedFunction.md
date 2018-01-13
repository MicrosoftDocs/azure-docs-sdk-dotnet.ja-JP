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
            ユーザーを表しますは、Azure Cosmos DB サービスで関数を定義します。
            </summary>
    <remarks>
            Azure の Cosmos DB には、JavaScript ユーザー定義関数 (Udf) は、データベースに格納され、クエリ内で使用できますがサポートしています。 クエリで Udf を使用する方法について http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration を参照してください。
            JavaScript での Udf の実装の詳細については http://azure.microsoft.com/documentation/articles/documentdb-programming/#udf を参照してください。
            </remarks>
    <example>
            次の例では、登録および Udf を使用する方法を示します。
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Azure Cosmos DB サービスのクラスです。
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
            取得または Azure Cosmos DB サービスのユーザー定義関数の本体を設定します。
            </summary>
        <value>ユーザーの本体は、関数を定義します。</value>
        <remarks>これは、有効な JavaScript 関数の例:"function (入力) {戻り input.toLowerCase();}"でなければなりません。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>