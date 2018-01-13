<Type Name="IWithDatabaseDtuMin" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Update.IWithDatabaseDtuMin">
  <TypeSignature Language="C#" Value="public interface IWithDatabaseDtuMin" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDatabaseDtuMin" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Update.IWithDatabaseDtuMin" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDatabaseDtuMin" />
  <TypeSignature Language="F#" Value="type IWithDatabaseDtuMin = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            データベースの DTU の最小値を設定するように SQL 弾力性プール定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Update.IUpdate WithDatabaseDtuMin (int databaseDtuMin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Update.IUpdate WithDatabaseDtuMin(int32 databaseDtuMin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Update.IWithDatabaseDtuMin.WithDatabaseDtuMin(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDatabaseDtuMin (databaseDtuMin As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDatabaseDtuMin : int -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Update.IUpdate" Usage="iWithDatabaseDtuMin.WithDatabaseDtuMin databaseDtuMin" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseDtuMin" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="databaseDtuMin">すべての SQL Azure データベースの最小 DTU です。</param>
        <summary>
            すべての SQL Azure データベースのことが保証されます最小 DTU を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>