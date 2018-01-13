<Type Name="SecurityRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SecurityRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SecurityRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SecurityRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SecurityRulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            SecurityRulesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, securityRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="securityRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkSecurityGroupName">
            ネットワーク セキュリティ グループの名前。
            </param>
        <param name="securityRuleName">
            セキュリティの規則の名前。
            </param>
        <param name="securityRuleParameters">
            作成または更新ネットワーク セキュリティ ルール操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または指定したネットワーク セキュリティ グループのセキュリティの規則を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkSecurityGroupName">
            ネットワーク セキュリティ グループの名前。
            </param>
        <param name="securityRuleName">
            セキュリティの規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したネットワーク セキュリティ ルールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner securityRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, securityRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="securityRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkSecurityGroupName">
            ネットワーク セキュリティ グループの名前。
            </param>
        <param name="securityRuleName">
            セキュリティの規則の名前。
            </param>
        <param name="securityRuleParameters">
            作成または更新ネットワーク セキュリティ ルール操作に渡されるパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または指定したネットワーク セキュリティ グループのセキュリティの規則を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkSecurityGroupName">
            ネットワーク セキュリティ グループの名前。
            </param>
        <param name="securityRuleName">
            セキュリティの規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したネットワーク セキュリティ ルールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, string securityRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.GetAsync (operations, resourceGroupName, networkSecurityGroupName, securityRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="securityRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkSecurityGroupName">
            ネットワーク セキュリティ グループの名前。
            </param>
        <param name="securityRuleName">
            セキュリティの規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したネットワーク セキュリティ ルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="networkSecurityGroupName">
            ネットワーク セキュリティ グループの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ネットワーク セキュリティ グループ内のすべてのセキュリティ規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.SecurityRulesOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.ISecurityRulesOperations" RefType="this" />
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
            ネットワーク セキュリティ グループ内のすべてのセキュリティ規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>