<Type Name="IBackupsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations">
  <TypeSignature Language="C#" Value="public interface IBackupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupsOperations" />
  <TypeSignature Language="F#" Value="type IBackupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            BackupsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TriggerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; TriggerWithHttpMessagesAsync (string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; TriggerWithHttpMessagesAsync(string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupsOperations.TriggerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupsOperations.TriggerWithHttpMessagesAsync (vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters, customHeaders, cancellationToken)" />
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
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource" />
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
            バックアップ項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップ アイテムに関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            どのバックアップ ニーズをトリガーするためのバックアップ アイテムです。
            </param>
        <param name="parameters">
            バックアップのリソース要求
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定のバックアップ項目のバックアップをトリガーします。 これは非同期操作です。 操作の状態を確認するには、GetProtectedItemOperationResult API を呼び出します。
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