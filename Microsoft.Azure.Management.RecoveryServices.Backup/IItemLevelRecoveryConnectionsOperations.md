<Type Name="IItemLevelRecoveryConnectionsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations">
  <TypeSignature Language="C#" Value="public interface IItemLevelRecoveryConnectionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IItemLevelRecoveryConnectionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IItemLevelRecoveryConnectionsOperations" />
  <TypeSignature Language="F#" Value="type IItemLevelRecoveryConnectionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ItemLevelRecoveryConnectionsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ProvisionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ProvisionWithHttpMessagesAsync (string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ProvisionWithHttpMessagesAsync(string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations.ProvisionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ProvisionWithHttpMessagesAsync : string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iItemLevelRecoveryConnectionsOperations.ProvisionWithHttpMessagesAsync (vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            バックアップのデータへの iSCSI 接続を呼び出すスクリプトを準備します。 このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。 これは非同期操作です。 プロビジョニングの状態を確認するには、GetProtectedItemOperationResult API を呼び出します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RevokeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RevokeWithHttpMessagesAsync (string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RevokeWithHttpMessagesAsync(string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IItemLevelRecoveryConnectionsOperations.RevokeWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RevokeWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iItemLevelRecoveryConnectionsOperations.RevokeWithHttpMessagesAsync (vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>