<Type Name="BackupStorageConfigsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupStorageConfigsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupStorageConfigsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupStorageConfigsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupStorageConfigsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            BackupStorageConfigsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig Get (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig Get(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupStorageConfigsOperations, resourceGroupName As String, vaultName As String) As BackupStorageConfig" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Get (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <summary>
            リソースの記憶域構成をフェッチします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースの記憶域構成をフェッチします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Update(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Update (operations, resourceGroupName, vaultName, backupStorageConfig)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="backupStorageConfig" Type="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="backupStorageConfig">
            バックアップ記憶域の構成。
            </param>
        <summary>
            更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.UpdateAsync (operations, resourceGroupName, vaultName, backupStorageConfig, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="backupStorageConfig" Type="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="backupStorageConfig">
            バックアップ記憶域の構成。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>