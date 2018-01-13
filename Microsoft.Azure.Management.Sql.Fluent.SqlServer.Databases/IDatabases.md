<Type Name="IDatabases" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases">
  <TypeSignature Language="C#" Value="public interface IDatabases" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDatabases" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDatabases" />
  <TypeSignature Language="F#" Value="type IDatabases = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            SQL Server から ElasticPools にアクセスするエントリ ポイントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Define">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank Define (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank Define(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.Define(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Define (databaseName As String) As IBlank" />
      <MemberSignature Language="F#" Value="abstract member Define : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank" Usage="iDatabases.Define databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank</ReturnType>
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
        <return>データベースの引数を指定するステージを返します。</return>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.Delete(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (databaseName As String)" />
      <MemberSignature Language="F#" Value="abstract member Delete : string -&gt; unit" Usage="iDatabases.Delete databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName">削除するデータベースの名前です。</param>
        <summary>
            サーバーの指定したデータベースを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.DeleteAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iDatabases.DeleteAsync (databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="databaseName">削除するデータベースの名前です。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            サーバーの指定したデータベースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>削除操作の観測可能なオブジェクトです。</return>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase Get (string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase Get(string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.Get(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (databaseName As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member Get : string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iDatabases.Get databaseName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseName">Sql データベースの名前を取得します。</param>
        <summary>
            特定の sql データベースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQL Server で使用してデータベースを返します。</return>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; List ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; List() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Databases.IDatabases.List" />
      <MemberSignature Language="VB.NET" Value="Public Function List () As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member List : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iDatabases.List " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サーバーのすべてのデータベースを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サーバーのデータベースの一覧です。</return>
      </Docs>
    </Member>
  </Members>
</Type>