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
            <span data-ttu-id="823eb-101">データベースの DTU の最小値を設定するように SQL 弾力性プール定義します。</span><span class="sxs-lookup"><span data-stu-id="823eb-101">The SQL Elastic Pool definition to set the minimum DTU for database.</span></span>
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
        <param name="databaseDtuMin"><span data-ttu-id="823eb-102">すべての SQL Azure データベースの最小 DTU です。</span><span class="sxs-lookup"><span data-stu-id="823eb-102">Minimum DTU for all SQL Azure databases.</span></span></param>
        <summary>
            <span data-ttu-id="823eb-103">すべての SQL Azure データベースのことが保証されます最小 DTU を設定します。</span><span class="sxs-lookup"><span data-stu-id="823eb-103">Sets the minimum DTU all SQL Azure Databases are guaranteed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="823eb-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="823eb-104">The next stage of definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>