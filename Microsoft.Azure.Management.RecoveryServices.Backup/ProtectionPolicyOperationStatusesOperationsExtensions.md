<Type Name="ProtectionPolicyOperationStatusesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionPolicyOperationStatusesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionPolicyOperationStatusesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionPolicyOperationStatusesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ProtectionPolicyOperationStatusesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionPolicyOperationStatusesOperations, vaultName As String, resourceGroupName As String, policyName As String, operationId As String) As OperationStatus" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.Get (operations, vaultName, resourceGroupName, policyName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="policyName">
            バックアップ ポリシー名を持つ操作の状態をフェッチする必要があります。
            </param>
        <param name="operationId">
            操作 ID をフェッチする必要がある状態が操作を表します。
            </param>
        <summary>
            バックアップ、復元など、非同期操作のステータスを提供します。
            進行中、完了または失敗の状態を指定できます。 操作のすべての可能な状態の操作のステータスの列挙型を参照することができます。 一部の操作は、ジョブを作成します。 このメソッドは、操作に関連付けられているジョブの一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations operations, string vaultName, string resourceGroupName, string policyName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, policyName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionPolicyOperationStatusesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="policyName">
            バックアップ ポリシー名を持つ操作の状態をフェッチする必要があります。
            </param>
        <param name="operationId">
            操作 ID をフェッチする必要がある状態が操作を表します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            バックアップ、復元など、非同期操作のステータスを提供します。
            進行中、完了または失敗の状態を指定できます。 操作のすべての可能な状態の操作のステータスの列挙型を参照することができます。 一部の操作は、ジョブを作成します。 このメソッドは、操作に関連付けられているジョブの一覧を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>