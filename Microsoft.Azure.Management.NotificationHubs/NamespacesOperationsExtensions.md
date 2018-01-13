<Type Name="NamespacesOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NamespacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NamespacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NamespacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NamespacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDelete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <summary>
            既存の名前空間を削除します。 この操作には、名前空間の下の関連するすべての notificationHubs も削除されます。
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の名前空間を削除します。 この操作には、名前空間の下の関連するすべての notificationHubs も削除されます。
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As INamespacesOperations, parameters As CheckAvailabilityParameters) As CheckAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            名前空間の名前。
            </param>
        <summary>
            すべての Azure サブスクリプション間、指定されたサービス名前空間の可用性を確認します。 これは、機能は、ドメイン名でサービス名前空間の名前に基づいて作成されるため便利です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CheckAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            名前空間の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての Azure サブスクリプション間、指定されたサービス名前空間の可用性を確認します。 これは、機能は、ドメイン名でサービス名前空間の名前に基づいて作成されるため便利です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource CreateOrUpdate (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource CreateOrUpdate(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As NamespaceCreateOrUpdateParameters) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="parameters">
            Namespace リソースを作成する指定されたパラメーター。
            </param>
        <summary>
            サービス名前空間の作成/更新します。 作成されると、この名前空間のリソース マニフェストは変更できません。 この操作は、べき等です。
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856303.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="parameters">
            Namespace リソースを作成する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サービス名前空間の作成/更新します。 作成されると、この名前空間のリソース マニフェストは変更できません。 この操作は、べき等です。
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856303.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As SharedAccessAuthorizationRuleCreateOrUpdateParameters) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            Aauthorization 規則の名前。
            </param>
        <param name="parameters">
            共有アクセス認証ルール。
            </param>
        <summary>
            名前空間の承認規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            Aauthorization 規則の名前。
            </param>
        <param name="parameters">
            共有アクセス認証ルール。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間の承認規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Delete(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Delete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <summary>
            既存の名前空間を削除します。 この操作には、名前空間の下の関連するすべての notificationHubs も削除されます。
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の名前空間を削除します。 この操作には、名前空間の下の関連するすべての notificationHubs も削除されます。
            <see href="http://msdn.microsoft.com/en-us/library/windowsazure/jj856296.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            承認規則の名前。
            </param>
        <summary>
            名前空間の承認規則を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            承認規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間の承認規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Get (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Get(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Get(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Get (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <summary>
            指定した名前空間の説明を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; GetAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; GetAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した名前空間の説明を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="authorizationRuleName">
            承認規則の名前。
            </param>
        <summary>
            名前で、名前空間の承認規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="authorizationRuleName">
            承認規則の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前で、名前空間の承認規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; List (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; List(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.List(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INamespacesOperations, resourceGroupName As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。 ResourceGroupName 値が null の場合、メソッドはサブスクリプション内のすべての名前空間を一覧表示されます。
            </param>
        <summary>
            リソース グループ内で使用できる名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAll (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAll(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAll(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INamespacesOperations) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <summary>
            ResourceGroups に関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAllAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            ResourceGroups に関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAllNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListAllNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            ResourceGroups に関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAllNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            ResourceGroups に関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。 ResourceGroupName 値が null の場合、メソッドはサブスクリプション内のすべての名前空間を一覧表示されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ内で使用できる名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <summary>
            名前空間の承認規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間の承認規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            名前空間の承認規則を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeys(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            指定した authorizationRule の名前空間の接続文字列。
            </param>
        <summary>
            名前空間に、プライマリとセカンダリ ConnectionStrings を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListKeysAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            指定した authorizationRule の名前空間の接続文字列。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前空間に、プライマリとセカンダリ ConnectionStrings を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListNext (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; ListNext(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNext(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of NamespaceResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            リソース グループ内で使用できる名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
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
            リソース グループ内で使用できる名前空間を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Patch (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource Patch(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Patch(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As NamespacePatchParameters) As NamespaceResource" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.Patch (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="parameters">
            Namespace リソースの修正プログラムを指定するパラメーターです。
            </param>
        <summary>
            修正プログラムの既存の名前空間
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; PatchAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt; PatchAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.PatchAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.PatchAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;PatchAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NamespacePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="parameters">
            Namespace リソースの修正プログラムを指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            修正プログラムの既存の名前空間
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As PolicykeyResource) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            指定した authorizationRule の名前空間の接続文字列。
            </param>
        <param name="parameters">
            Namespace 承認規則のキーを再生成する指定されたパラメーター。
            </param>
        <summary>
            Namespace の承認規則にプライマリ/セカンダリ キーが再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.NotificationHubs.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.NotificationHubs.INamespacesOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NamespacesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="namespaceName">
            名前空間の名前。
            </param>
        <param name="authorizationRuleName">
            指定した authorizationRule の名前空間の接続文字列。
            </param>
        <param name="parameters">
            Namespace 承認規則のキーを再生成する指定されたパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Namespace の承認規則にプライマリ/セカンダリ キーが再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>