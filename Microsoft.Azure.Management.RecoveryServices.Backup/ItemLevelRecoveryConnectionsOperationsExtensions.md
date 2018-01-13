<Type Name="ItemLevelRecoveryConnectionsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ItemLevelRecoveryConnectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ItemLevelRecoveryConnectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ItemLevelRecoveryConnectionsOperationsExtensions = class" />
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
            ItemLevelRecoveryConnectionsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Provision">
      <MemberSignature Language="C#" Value="public static void Provision (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Provision(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Provision(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Provision (operations As IItemLevelRecoveryConnectionsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String, parameters As ILRRequestResource)" />
      <MemberSignature Language="F#" Value="static member Provision : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Provision (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
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
            項目の名前のファイルとフォルダーを復元するバックアップされます。
            </param>
        <param name="recoveryPointId">
            バックアップは、データの回復ポイントの ID を表します。 iSCSI 接続は、このバックアップ データのプロビジョニングされます。
            </param>
        <param name="parameters">
            リソース ILR 要求
            </param>
        <summary>
            バックアップのデータへの iSCSI 接続を呼び出すスクリプトを準備します。
            このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。 これは非同期操作です。 プロビジョニングの状態を確認するには、GetProtectedItemOperationResult API を呼び出します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ProvisionAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ProvisionAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.ProvisionAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ProvisionAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.ProvisionAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions/&lt;ProvisionAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
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
            項目の名前のファイルとフォルダーを復元するバックアップされます。
            </param>
        <param name="recoveryPointId">
            バックアップは、データの回復ポイントの ID を表します。 iSCSI 接続は、このバックアップ データのプロビジョニングされます。
            </param>
        <param name="parameters">
            リソース ILR 要求
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            バックアップのデータへの iSCSI 接続を呼び出すスクリプトを準備します。
            このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。 これは非同期操作です。 プロビジョニングの状態を確認するには、GetProtectedItemOperationResult API を呼び出します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revoke">
      <MemberSignature Language="C#" Value="public static void Revoke (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Revoke(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Revoke(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Revoke (operations As IItemLevelRecoveryConnectionsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String)" />
      <MemberSignature Language="F#" Value="static member Revoke : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.Revoke (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
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
            項目の名前のファイルとフォルダーを復元するバックアップされます。
            </param>
        <param name="recoveryPointId">
            バックアップは、データの回復ポイントの ID を表します。 このバックアップ データの iSCSI 接続は取り消されます。
            </param>
        <summary>
            スクリプトをダウンロードするために使用する iSCSI 接続を取り消します。
            このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。 これは非同期操作です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RevokeAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RevokeAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.RevokeAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions.RevokeAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ItemLevelRecoveryConnectionsOperationsExtensions/&lt;RevokeAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
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
            項目の名前のファイルとフォルダーを復元するバックアップされます。
            </param>
        <param name="recoveryPointId">
            バックアップは、データの回復ポイントの ID を表します。 このバックアップ データの iSCSI 接続は取り消されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            スクリプトをダウンロードするために使用する iSCSI 接続を取り消します。
            このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。 これは非同期操作です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>