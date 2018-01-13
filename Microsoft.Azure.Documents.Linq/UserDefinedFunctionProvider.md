<Type Name="UserDefinedFunctionProvider" FullName="Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider">
  <TypeSignature Language="C#" Value="public static class UserDefinedFunctionProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UserDefinedFunctionProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class UserDefinedFunctionProvider" />
  <TypeSignature Language="F#" Value="type UserDefinedFunctionProvider = class" />
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
            Cosmos DB の Azure サービスでの Linq クエリを使用してユーザー定義関数を呼び出すためのヘルパー クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invoke">
      <MemberSignature Language="C#" Value="public static object Invoke (string udfName, params object[] arguments);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object Invoke(string udfName, object[] arguments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider.Invoke(System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Invoke (udfName As String, ParamArray arguments As Object()) As Object" />
      <MemberSignature Language="F#" Value="static member Invoke : string * obj[] -&gt; obj" Usage="Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider.Invoke (udfName, arguments)" />
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
        <Parameter Name="udfName" Type="System.String" />
        <Parameter Name="arguments" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="udfName">ユーザー定義関数名</param>
        <param name="arguments">UserDefinedFunction の引数</param>
        <summary>
            Cosmos DB の Azure サービスでの Linq クエリを使用してユーザー定義関数を呼び出すヘルパー メソッドです。
            </summary>
        <returns />
        <remarks>
            これは、LINQ の式内で使用するスタブのヘルパー メソッドです。 直接呼び出すことができません。 詳細については、LINQ プロバイダー http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#linq-to-documentdb-sql を参照してください。
            ユーザー定義関数の詳細については http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration を参照してください。
            </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />
        <example>
          <code language="c#"><![CDATA[
             await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "calculateTax", Body = @"function(amt) { return amt * 0.05; }" });
             var queryable = client.CreateDocumentQuery<Book>(collectionLink).Select(b => UserDefinedFunctionProvider.Invoke("calculateTax", b.Price));
             
            // Equivalent to SELECT * FROM books b WHERE udf.toLowerCase(b.title) = 'war and peace'" 
            await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "toLowerCase", Body = @"function(s) { return s.ToLowerCase(); }" });
            queryable = client.CreateDocumentQuery<Book>(collectionLink).Where(b => UserDefinedFunctionProvider.Invoke("toLowerCase", b.Title) == "war and peace");
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>