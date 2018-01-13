<Type Name="ServersOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ServersOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="parameters">
            作成またはサーバーを更新するための必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure SQL サーバーを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateFirewallRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; CreateOrUpdateFirewallRuleAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; CreateOrUpdateFirewallRuleAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateFirewallRuleAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateFirewallRuleAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateFirewallRuleAsync (operations, resourceGroupName, serverName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;CreateOrUpdateFirewallRuleAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="firewallRuleName">
            Azure SQL server のファイアウォール ルールの名前。
            </param>
        <param name="parameters">
            作成または更新するファイアウォール規則の必須パラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または Azure SQL サーバーのファイアウォール ルールを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;DeleteAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            SQL サーバーを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFirewallRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteFirewallRuleAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteFirewallRuleAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteFirewallRuleAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteFirewallRuleAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteFirewallRuleAsync (operations, resourceGroupName, serverName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;DeleteFirewallRuleAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="firewallRuleName">
            Azure SQL server のファイアウォール ルールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL サーバーのファイアウォール ルールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; GetByResourceGroupAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; GetByResourceGroupAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetByResourceGroupAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByResourceGroupAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetByResourceGroupAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;GetByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL サーバーに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFirewallRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; GetFirewallRuleAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; GetFirewallRuleAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetFirewallRuleAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFirewallRuleAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetFirewallRuleAsync (operations, resourceGroupName, serverName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;GetFirewallRuleAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="firewallRuleName">
            Azure SQL server のファイアウォール ルールの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL サーバーのファイアウォール規則を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceObjectiveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt; GetServiceObjectiveAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string serviceObjectiveName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt; GetServiceObjectiveAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string serviceObjectiveName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetServiceObjectiveAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetServiceObjectiveAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetServiceObjectiveAsync (operations, resourceGroupName, serverName, serviceObjectiveName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;GetServiceObjectiveAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="serviceObjectiveName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="serviceObjectiveName">
            取得するサービス目標の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベース サービス目標に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL サーバーに関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL サーバーに関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFirewallRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt; ListFirewallRulesAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt; ListFirewallRulesAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListFirewallRulesAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFirewallRulesAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListFirewallRulesAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListFirewallRulesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL server のファイアウォール ルールの一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceObjectivesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt; ListServiceObjectivesAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt; ListServiceObjectivesAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListServiceObjectivesAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceObjectivesAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListServiceObjectivesAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListServiceObjectivesAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL データベースのサービス目標に関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListUsagesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            Azure SQL サーバーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure SQL サーバーの使用状況に関する情報を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>