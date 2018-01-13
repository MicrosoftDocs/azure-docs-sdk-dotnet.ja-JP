<Type Name="IWithMaxSizeBytes" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithMaxSizeBytes">
  <TypeSignature Language="C#" Value="public interface IWithMaxSizeBytes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMaxSizeBytes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithMaxSizeBytes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMaxSizeBytes" />
  <TypeSignature Language="F#" Value="type IWithMaxSizeBytes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            バイト単位でデータベースの最大サイズを設定する SQL データベースの定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMaxSizeBytes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateWithElasticPoolOptions WithMaxSizeBytes (long maxSizeBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateWithElasticPoolOptions WithMaxSizeBytes(int64 maxSizeBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithMaxSizeBytes.WithMaxSizeBytes(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMaxSizeBytes (maxSizeBytes As Long) As IWithCreateWithElasticPoolOptions" />
      <MemberSignature Language="F#" Value="abstract member WithMaxSizeBytes : int64 -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateWithElasticPoolOptions" Usage="iWithMaxSizeBytes.WithMaxSizeBytes maxSizeBytes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IWithCreateWithElasticPoolOptions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxSizeBytes" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSizeBytes">
            Azure SQL データベースの最大サイズは、バイトで表現されます。 注: (各エディションで配置されている制限事項) だけでなく、次のサイズのみがサポートされて: {100 MB | 500 MB | 1 GB | 5 GB | 10 GB | 20 GB | 30 GB. 150 GB |200 GB しています. 500 GB}。
            </param>
        <summary>
            (バイト単位) SQL データベースの最大サイズを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>