<Type Name="IWithDatabaseDtuMax" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabaseDtuMax">
  <TypeSignature Language="C#" Value="public interface IWithDatabaseDtuMax" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDatabaseDtuMax" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabaseDtuMax" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDatabaseDtuMax" />
  <TypeSignature Language="F#" Value="type IWithDatabaseDtuMax = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            SQL 弾力性プール定義を 1 つのデータベースの最大 DTU を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithDatabaseDtuMax (int databaseDtuMax);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithDatabaseDtuMax(int32 databaseDtuMax) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDatabaseDtuMax.WithDatabaseDtuMax(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDatabaseDtuMax (databaseDtuMax As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDatabaseDtuMax : int -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDatabaseDtuMax.WithDatabaseDtuMax databaseDtuMax" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseDtuMax" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="databaseDtuMax">最大の DTU の 1 つの SQL Azure データベースを使用できます。</param>
        <summary>
            いずれかの SQL Azure データベースが使用できる最大の DTU を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>