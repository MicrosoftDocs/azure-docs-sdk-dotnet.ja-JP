<Type Name="IWithDtu" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDtu">
  <TypeSignature Language="C#" Value="public interface IWithDtu" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDtu" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDtu" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDtu" />
  <TypeSignature Language="F#" Value="type IWithDtu = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            弾力性プールの共有の DTU の数を設定するように SQL 弾力性プール定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDtu">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithDtu (int dtu);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate WithDtu(int32 dtu) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithDtu.WithDtu(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDtu (dtu As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDtu : int -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate" Usage="iWithDtu.WithDtu dtu" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlElasticPool.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dtu" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="dtu">合計では、SQL Azure データベースの弾力性プールの DTU が共有されます。</param>
        <summary>
            SQL Azure データベースの弾力性プールの合計の DTU の共有を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>