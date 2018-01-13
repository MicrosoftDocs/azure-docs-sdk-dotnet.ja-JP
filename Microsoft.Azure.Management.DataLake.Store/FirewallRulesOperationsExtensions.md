<Type Name="FirewallRulesOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FirewallRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FirewallRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FirewallRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FirewallRulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            FirewallRulesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String, parameters As FirewallRule) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, firewallRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを追加または置き換えるファイアウォール規則の名前。
            </param>
        <param name="firewallRuleName">
            作成または更新するファイアウォール規則の名前。
            </param>
        <param name="parameters">
            ファイアウォール規則を作成または指定されたパラメーター。
            </param>
        <summary>
            作成または指定されたファイアウォール規則を更新します。 更新中に、この新しいファイアウォール ルールで指定した名前のファイアウォール ルールが置き換えられます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            Data Lake Store アカウントを追加または置き換えるファイアウォール規則の名前。
            </param>
        <param name="firewallRuleName">
            作成または更新するファイアウォール規則の名前。
            </param>
        <param name="parameters">
            ファイアウォール規則を作成または指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または指定されたファイアウォール規則を更新します。 更新中に、この新しいファイアウォール ルールで指定した名前のファイアウォール ルールが置き換えられます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Delete (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール規則を削除する Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            削除するファイアウォール規則の名前。
            </param>
        <summary>
            指定された Data Lake Store アカウントから指定されたファイアウォール ルールを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール規則を削除する Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            削除するファイアウォール規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウントから指定されたファイアウォール ルールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Get (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Get(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Get (operations, resourceGroupName, accountName, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            取得するファイアウォール規則の名前。
            </param>
        <summary>
            指定された Data Lake Store のファイアウォール ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            取得するファイアウォール規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store のファイアウォール ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String) As IPage(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。
            </param>
        <summary>
            指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールの取得元の Data Lake Store アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IFirewallRulesOperations, nextPageLink As String) As IPage(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Store アカウント内での Data Lake Store のファイアウォール ルールを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Update (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule Update(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IFirewallRulesOperations, resourceGroupName As String, accountName As String, firewallRuleName As String, Optional parameters As UpdateFirewallRuleParameters = null) As FirewallRule" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters -&gt; Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.Update (operations, resourceGroupName, accountName, firewallRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールを更新するために、Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            更新するファイアウォール規則の名前。
            </param>
        <param name="parameters">
            ファイアウォール ルールの更新に指定するパラメーターです。
            </param>
        <summary>
            指定されたファイアウォール規則を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations operations, string resourceGroupName, string accountName, string firewallRuleName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Store.FirewallRulesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Store.IFirewallRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateFirewallRuleParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Data Lake Store アカウントが含まれている Azure リソース グループの名前。
            </param>
        <param name="accountName">
            ファイアウォール ルールを更新するために、Data Lake Store アカウントの名前。
            </param>
        <param name="firewallRuleName">
            更新するファイアウォール規則の名前。
            </param>
        <param name="parameters">
            ファイアウォール ルールの更新に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたファイアウォール規則を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>