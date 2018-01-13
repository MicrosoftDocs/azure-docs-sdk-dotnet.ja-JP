<Type Name="RestoresOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RestoresOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RestoresOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RestoresOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RestoresOperationsExtensions = class" />
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
            RestoresOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static void Trigger (this Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trigger(class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.Trigger(Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Trigger (operations As IRestoresOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String, parameters As RestoreRequestResource)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.Trigger (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource" />
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
        <param name="fabricName">
            バックアップされた項目に関連付けられたファブリックの名前です。
            </param>
        <param name="containerName">
            バックアップされた項目に関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            復元する項目をバックアップします。
            </param>
        <param name="recoveryPointId">
            バックアップを復元するデータを表す回復ポイントの ID です。
            </param>
        <param name="parameters">
            復元要求のリソース
            </param>
        <summary>
            指定したデータのバックアップを復元します。 これは非同期操作です。
            この API 呼び出しの状態を確認するには、GetProtectedItemOperationResult API を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TriggerAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TriggerAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.TriggerAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions.TriggerAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RestoresOperationsExtensions/&lt;TriggerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource" />
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
        <param name="fabricName">
            バックアップされた項目に関連付けられたファブリックの名前です。
            </param>
        <param name="containerName">
            バックアップされた項目に関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            復元する項目をバックアップします。
            </param>
        <param name="recoveryPointId">
            バックアップを復元するデータを表す回復ポイントの ID です。
            </param>
        <param name="parameters">
            復元要求のリソース
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したデータのバックアップを復元します。 これは非同期操作です。
            この API 呼び出しの状態を確認するには、GetProtectedItemOperationResult API を使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>