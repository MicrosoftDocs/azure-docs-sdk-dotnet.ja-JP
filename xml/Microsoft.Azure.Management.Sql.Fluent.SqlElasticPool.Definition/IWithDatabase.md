<Type Name="IWithDatabase" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase">
  <TypeSignature Language="C#" Value="public interface IWithDatabase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDatabase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDatabase" />
  <TypeSignature Language="F#" Value="type IWithDatabase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a1da3-101">弾力性プール内にデータベースを追加する SQL 弾力性プール定義します。</span><span class="sxs-lookup"><span data-stu-id="a1da3-101">The SQL Elastic Pool definition to add the Database in the elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase (Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase database);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase(class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase database) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase.WithExistingDatabase(Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDatabase (database As ISqlDatabase) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDatabase : Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabase.WithExistingDatabase database" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="database" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" />
      </Parameters>
      <Docs>
        <param name="database"><span data-ttu-id="a1da3-102">SQL 弾力性プールに追加するデータベース インスタンス。</span><span class="sxs-lookup"><span data-stu-id="a1da3-102">Database instance to be added in SQL elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="a1da3-103">SQL 弾力性プールのデータベースを追加します。</span><span class="sxs-lookup"><span data-stu-id="a1da3-103">Adds the database in the SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a1da3-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a1da3-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithExistingDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase.WithExistingDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingDatabase (databaseName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabase.WithExistingDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="a1da3-105">弾力性プールに追加する既存のデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="a1da3-105">Name of the existing database to be added in the elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="a1da3-106">SQL 弾力性プール内の既存のデータベースを追加します。</span><span class="sxs-lookup"><span data-stu-id="a1da3-106">Adds an existing database in the SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a1da3-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a1da3-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithNewDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithNewDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabase.WithNewDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDatabase (databaseName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabase.WithNewDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="a1da3-108">弾力性プールに追加する新しいデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="a1da3-108">Name of the new database to be added in the elastic pool.</span></span></param>
        <summary>
            <span data-ttu-id="a1da3-109">SQL 弾力性プールに新しいデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="a1da3-109">Creates a new database in the SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a1da3-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a1da3-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>