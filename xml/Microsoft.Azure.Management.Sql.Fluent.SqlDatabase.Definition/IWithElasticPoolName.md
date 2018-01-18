<Type Name="IWithElasticPoolName" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithElasticPoolName">
  <TypeSignature Language="C#" Value="public interface IWithElasticPoolName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithElasticPoolName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithElasticPoolName" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithElasticPoolName" />
  <TypeSignature Language="F#" Value="type IWithElasticPoolName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b6559-101">弾力性プール データベースを設定する SQL データベースの定義。</span><span class="sxs-lookup"><span data-stu-id="b6559-101">The SQL Database definition to set the elastic pool for database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase WithExistingElasticPool (Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool sqlElasticPool);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase WithExistingElasticPool(class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool sqlElasticPool) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithElasticPoolName.WithExistingElasticPool(Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingElasticPool (sqlElasticPool As ISqlElasticPool) As IWithExistingDatabase" />
      <MemberSignature Language="F#" Value="abstract member WithExistingElasticPool : Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase" Usage="iWithElasticPoolName.WithExistingElasticPool sqlElasticPool" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlElasticPool" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool" />
      </Parameters>
      <Docs>
        <param name="sqlElasticPool"><span data-ttu-id="b6559-102">SQL データベース。</span><span class="sxs-lookup"><span data-stu-id="b6559-102">For the SQL Database.</span></span></param>
        <summary>
            <span data-ttu-id="b6559-103">Sql データベースの既存のエラスティック プールを設定します。</span><span class="sxs-lookup"><span data-stu-id="b6559-103">Sets the existing elastic pool for the SQLDatabase.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b6559-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b6559-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase WithExistingElasticPool (string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase WithExistingElasticPool(string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithElasticPoolName.WithExistingElasticPool(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingElasticPool (elasticPoolName As String) As IWithExistingDatabase" />
      <MemberSignature Language="F#" Value="abstract member WithExistingElasticPool : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase" Usage="iWithElasticPoolName.WithExistingElasticPool elasticPoolName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elasticPoolName"><span data-ttu-id="b6559-105">SQL データベース。</span><span class="sxs-lookup"><span data-stu-id="b6559-105">For the SQL Database.</span></span></param>
        <summary>
            <span data-ttu-id="b6559-106">Sql データベースの既存のエラスティック プールを設定します。</span><span class="sxs-lookup"><span data-stu-id="b6559-106">Sets the existing elastic pool for the SQLDatabase.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b6559-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b6559-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewElasticPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase WithNewElasticPool (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; sqlElasticPool);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase WithNewElasticPool(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; sqlElasticPool) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithElasticPoolName.WithNewElasticPool(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewElasticPool (sqlElasticPool As ICreatable(Of ISqlElasticPool)) As IWithExistingDatabase" />
      <MemberSignature Language="F#" Value="abstract member WithNewElasticPool : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase" Usage="iWithElasticPoolName.WithNewElasticPool sqlElasticPool" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithExistingDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlElasticPool" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlElasticPool&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlElasticPool"><span data-ttu-id="b6559-108">SQL データベースに対して作成される新しい弾力性プールの作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="b6559-108">Creatable definition for new elastic pool to be created for the SQL Database.</span></span></param>
        <summary>
            <span data-ttu-id="b6559-109">新しい弾力性プールの sql データベースのセット、データベースの作成中に、新しい柔軟なプールが作成されます。</span><span class="sxs-lookup"><span data-stu-id="b6559-109">Sets the new elastic pool for the SQLDatabase, this will create a new elastic pool while creating database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b6559-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b6559-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>