<Type Name="IWithDatabase" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithDatabase">
  <TypeSignature Language="C#" Value="public interface IWithDatabase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDatabase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithDatabase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDatabase" />
  <TypeSignature Language="F#" Value="type IWithDatabase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            データベースを指定するための SQL Server 定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewDatabase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewDatabase (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewDatabase(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithDatabase.WithNewDatabase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewDatabase (databaseName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewDatabase : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate" Usage="iWithDatabase.WithNewDatabase databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName">作成するデータベースの名前。</param>
        <summary>
            SQL Server で新しいデータベースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQL Server の定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>