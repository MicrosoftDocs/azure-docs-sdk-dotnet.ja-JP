<Type Name="IFirewallRules" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules">
  <TypeSignature Language="C#" Value="public interface IFirewallRules" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFirewallRules" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFirewallRules" />
  <TypeSignature Language="F#" Value="type IFirewallRules = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            SQL Server から FirewallRules にアクセスするエントリ ポイントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Define">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank Define (string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank Define(string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.Define(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Define (firewallRuleName As String) As IBlank" />
      <MemberSignature Language="F#" Value="abstract member Define : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank" Usage="iFirewallRules.Define firewallRuleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName">作成するファイアウォール規則の名前です。</param>
        <summary>
            SQL Server で、新しいファイアウォール ルールを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ファイアウォール ルールの引数を指定するステージを返します。</return>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.Delete(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (firewallRuleName As String)" />
      <MemberSignature Language="F#" Value="abstract member Delete : string -&gt; unit" Usage="iFirewallRules.Delete firewallRuleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName">削除するファイアウォール規則の名前です。</param>
        <summary>
            サーバーで指定されたファイアウォール規則を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.DeleteAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iFirewallRules.DeleteAsync (firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName">削除するファイアウォール規則の名前です。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            サーバーで指定されたファイアウォール規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>削除操作の観測可能なオブジェクトです。</return>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule Get (string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule Get(string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.Get(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (firewallRuleName As String) As ISqlFirewallRule" />
      <MemberSignature Language="F#" Value="abstract member Get : string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule" Usage="iFirewallRules.Get firewallRuleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName">ファイアウォール規則の名前を取得します。</param>
        <summary>
            特定のファイアウォール ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQL Server で SqlFirewall 規則を返します。</return>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; List ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; List() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.List" />
      <MemberSignature Language="VB.NET" Value="Public Function List () As IReadOnlyList(Of ISqlFirewallRule)" />
      <MemberSignature Language="F#" Value="abstract member List : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;" Usage="iFirewallRules.List " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サーバーのすべてのファイアウォール ルールを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サーバーのファイアウォール ルールの一覧です。</return>
      </Docs>
    </Member>
  </Members>
</Type>