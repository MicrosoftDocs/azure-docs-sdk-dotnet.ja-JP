<Type Name="NamespacesOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NamespacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NamespacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NamespacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NamespacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            NamespacesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="parameters">
            名前空間リソースを作成する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、サービス名前空間を更新します。 作成されると、この名前空間のリソース マニフェストは変更できません。 この操作は、べき等です。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639408.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の名前空間を削除します。 この操作には、名前空間の下の関連するすべてのリソースも削除されます。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639389.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityMethodAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityMethodAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityMethodAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CheckNameAvailabilityMethodAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityMethodAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CheckNameAvailabilityMethodAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;CheckNameAvailabilityMethodAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="name">
            名前空間の名前の可用性を確認する名前と名前空間の名前は、アルファベット、数字、およびハイフンのみを含めることができます。 名前空間は文字で始める必要があり、最後の文字または数字。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            付与名前空間の名前の可用性を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="parameters">
            名前空間リソースを作成する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、サービス名前空間を更新します。 作成されると、この名前空間のリソース マニフェストは変更できません。 この操作は、べき等です。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639408.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; rights, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; rights, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, rights, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="authorizationRuleName">
            Authorizationrule 名前です。
            </param>
        <param name="rights">
            ルールに関連付けられている権限。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または名前空間の承認規則を更新します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639410.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の名前空間を削除します。 この操作には、名前空間の下の関連するすべてのリソースも削除されます。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639389.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="authorizationRuleName">
            Authorizationrule 名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間の承認規則を削除します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639417.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した名前空間の説明を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639379.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="authorizationRuleName">
            Authorizationrule 名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ルールの名前で、名前空間の承認規則を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639392.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
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
            リソース グループに関係なく、サブスクリプション内で使用可能なすべての名前空間を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間の承認規則を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639376.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
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
            名前空間の承認規則を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639376.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内で使用できる名前空間を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
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
            リソース グループ内で使用できる名前空間を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; ListKeysAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; ListKeysAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListKeysAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="authorizationRuleName">
            Authorizationrule 名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間のプライマリとセカンダリの接続文字列を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639398.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
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
            リソース グループに関係なく、サブスクリプション内で使用可能なすべての名前空間を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, policykey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="policykey" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="authorizationRuleName">
            Authorizationrule 名前です。
            </param>
        <param name="policykey">
            再生成する必要があるキー。 使用可能な値が含まれます: 'PrimaryKey'、'SecondaryKey'
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間のプライマリまたはセカンダリの接続文字列を再生成します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt718977.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; UpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; UpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.UpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;UpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="parameters">
            名前空間リソースの更新に指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サービス名前空間を更新します。 作成されると、この名前空間のリソース マニフェストは変更できません。 この操作は、べき等です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>