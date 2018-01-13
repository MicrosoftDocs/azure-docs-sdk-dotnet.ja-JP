<Type Name="ISqlFirewallRules" FullName="Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRules">
  <TypeSignature Language="C#" Value="public interface ISqlFirewallRules : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IServersOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISqlFirewallRules implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IServersOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRules" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISqlFirewallRules&#xA;Implements IHasInner(Of IServersOperations), IHasManager(Of ISqlManager), ISupportsBatchCreation(Of ISqlFirewallRule), ISupportsDeletingById, ISupportsDeletingByParent, ISupportsGettingById(Of ISqlFirewallRule)" />
  <TypeSignature Language="F#" Value="type ISqlFirewallRules = interface&#xA;    interface ISupportsDeletingById&#xA;    interface ISupportsGettingById&lt;ISqlFirewallRule&gt;&#xA;    interface ISupportsBatchCreation&lt;ISqlFirewallRule&gt;&#xA;    interface ISupportsDeletingByParent&#xA;    interface IHasManager&lt;ISqlManager&gt;&#xA;    interface IHasInner&lt;IServersOperations&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IServersOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            SQL FirewallRule 管理 API へのエントリ ポイントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule GetBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule GetBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRules.GetBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (sqlServer As ISqlServer, name As String) As ISqlFirewallRule" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule" Usage="iSqlFirewallRules.GetBySqlServer (sqlServer, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlServer">SQLServer のインスタンス。</param>
        <param name="name">sql データベースの名前。</param>
        <summary>
            Sql Server インスタンスおよび FirewallRule 名に基づいて sql データベースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Sql データベースの変更できない形式です。</return>
      </Docs>
    </Member>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule GetBySqlServer (string resourceGroup, string sqlServerName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule GetBySqlServer(string resourceGroup, string sqlServerName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRules.GetBySqlServer(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (resourceGroup As String, sqlServerName As String, name As String) As ISqlFirewallRule" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule" Usage="iSqlFirewallRules.GetBySqlServer (resourceGroup, sqlServerName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="sqlServerName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroup">リソース グループの名前。</param>
        <param name="sqlServerName">sql Server の名前。</param>
        <param name="name">sql データベースの名前。</param>
        <summary>
            リソース グループ名、sql Server 名および FirewallRule 名に基づいて sql データベースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Sql データベースの変更できない形式です。</return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; ListBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; ListBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRules.ListBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (sqlServer As ISqlServer) As IReadOnlyList(Of ISqlFirewallRule)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;" Usage="iSqlFirewallRules.ListBySqlServer sqlServer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
      </Parameters>
      <Docs>
        <param name="sqlServer">SQLServer のインスタンス。</param>
        <summary>
            SQLServer に基づいて sql データベースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQLServer で SQLDatabases の一覧。</return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; ListBySqlServer (string resourceGroupName, string sqlServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; ListBySqlServer(string resourceGroupName, string sqlServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRules.ListBySqlServer(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (resourceGroupName As String, sqlServerName As String) As IReadOnlyList(Of ISqlFirewallRule)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : string * string -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;" Usage="iSqlFirewallRules.ListBySqlServer (resourceGroupName, sqlServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="sqlServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">リソースを一覧表示するリソース グループの名前。</param>
        <param name="sqlServerName">sql Server の名前。</param>
        <summary>
            指定されたリソース グループと sql Server で指定した型のリソースを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQLServer で SQLDatabases の一覧。</return>
      </Docs>
    </Member>
  </Members>
</Type>