<Type Name="DisasterRecoveryConfigsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DisasterRecoveryConfigsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DisasterRecoveryConfigsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DisasterRecoveryConfigsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DisasterRecoveryConfigsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            DisasterRecoveryConfigsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BreakPairing">
      <MemberSignature Language="C#" Value="public static void BreakPairing (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BreakPairing(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.BreakPairing(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BreakPairing (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String)" />
      <MemberSignature Language="F#" Value="static member BreakPairing : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.BreakPairing (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <summary>
            この操作は、災害復旧を無効にし、プライマリからセカンダリ名前空間への変更のレプリケーションを停止
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakPairingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BreakPairingAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BreakPairingAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.BreakPairingAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BreakPairingAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.BreakPairingAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;BreakPairingAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            この操作は、災害復旧を無効にし、プライマリからセカンダリ名前空間への変更のレプリケーションを停止
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityMethod">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult CheckNameAvailabilityMethod (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult CheckNameAvailabilityMethod(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailabilityMethod(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailabilityMethod (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, parameters As CheckNameAvailability) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityMethod : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability -&gt; Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailabilityMethod (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability" />
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
            パラメーターを指定した名前空間の名前の可用性を確認するには
            </param>
        <summary>
            付与名前空間の名前の可用性を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityMethodAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityMethodAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityMethodAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailabilityMethodAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityMethodAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CheckNameAvailabilityMethodAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;CheckNameAvailabilityMethodAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.CheckNameAvailability" />
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
            パラメーターを指定した名前空間の名前の可用性を確認するには
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
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery CreateOrUpdate (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery CreateOrUpdate(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String, parameters As ArmDisasterRecovery) As ArmDisasterRecovery" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery -&gt; Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, alias, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="parameters">
            エイリアス (障害回復の構成) を作成するために必要なパラメーター
            </param>
        <summary>
            作成するか、新しいエイリアス (障害回復の構成) の更新
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, alias, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="parameters">
            エイリアス (障害回復の構成) を作成するために必要なパラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、新しいエイリアス (障害回復の構成) の更新
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.Delete(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <summary>
            エイリアス (障害回復の構成) を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エイリアス (障害回復の構成) を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailOver">
      <MemberSignature Language="C#" Value="public static void FailOver (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void FailOver(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.FailOver(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub FailOver (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String)" />
      <MemberSignature Language="F#" Value="static member FailOver : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.FailOver (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <summary>
            envokes GEO DR フェールオーバーおよび再構成セカンダリ名前空間を指すエイリアス
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailOverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailOverAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailOverAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.FailOverAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailOverAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.FailOverAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;FailOverAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            envokes GEO DR フェールオーバーおよび再構成セカンダリ名前空間を指すエイリアス
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery Get (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery Get(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.Get(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String) As ArmDisasterRecovery" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <summary>
            プライマリまたはセカンダリ名前空間のエイリアス (障害回復の構成) を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プライマリまたはセカンダリ名前空間のエイリアス (障害回復の構成) を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule GetAuthorizationRule (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule GetAuthorizationRule(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String, authorizationRuleName As String) As SBAuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, alias, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="authorizationRuleName">
            Authorizationrule 名前です。
            </param>
        <summary>
            ルールの名前で、名前空間の承認規則を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639392.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, alias, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; List (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; List(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.List(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String) As IPage(Of ArmDisasterRecovery)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.List (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
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
        <summary>
            すべてのエイリアス (障害回復の構成) を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt; ListAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt; ListAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
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
            すべてのエイリアス (障害回復の構成) を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRules (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRules(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String) As IPage(Of SBAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <summary>
            名前空間の承認規則を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639376.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, alias, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
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
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As IDisasterRecoveryConfigsOperations, nextPageLink As String) As IPage(Of SBAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
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
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639376.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
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
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.AccessKeys ListKeys (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys ListKeys(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListKeys(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IDisasterRecoveryConfigsOperations, resourceGroupName As String, namespaceName As String, alias As String, authorizationRuleName As String) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.AccessKeys" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, alias, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
            </param>
        <param name="authorizationRuleName">
            Authorizationrule 名前です。
            </param>
        <summary>
            名前空間のプライマリとセカンダリの接続文字列を取得します。
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639398.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string resourceGroupName, string namespaceName, string alias, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, alias, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;ListKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
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
        <param name="alias">
            障害復旧構成の名前
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
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; ListNext (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt; ListNext(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListNext(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDisasterRecoveryConfigsOperations, nextPageLink As String) As IPage(Of ArmDisasterRecovery)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
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
            すべてのエイリアス (障害回復の構成) を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.DisasterRecoveryConfigsOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.ArmDisasterRecovery&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" RefType="this" />
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
            すべてのエイリアス (障害回復の構成) を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>