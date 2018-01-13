<Type Name="IVaultOperations" FullName="Microsoft.Azure.Management.BackupServices.IVaultOperations">
  <TypeSignature Language="C#" Value="public interface IVaultOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVaultOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IVaultOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVaultOperations" />
  <TypeSignature Language="F#" Value="type IVaultOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Azure Backup の拡張機能の資格情報コンテナーに関連する操作の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.CreateOrUpdateAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            所属する資格情報コンテナーにリソース グループの名前
            </param>
        <param name="resourceName">
            資格情報コンテナーの名前
            </param>
        <param name="parameters">
            パラメーターを作成または資格情報コンテナーの更新
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure バックアップ コンテナーを作成します。
            </summary>
        <returns>
            資格情報コンテナー情報です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.DeleteAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.DeleteAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            所属する資格情報コンテナーにリソース グループの名前
            </param>
        <param name="resourceName">
            資格情報コンテナーの名前
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Azure バックアップ コンテナーを削除します。
            </summary>
        <returns>
            資格情報コンテナー情報です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.GetAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            所属する資格情報コンテナーにリソース グループの名前
            </param>
        <param name="resourceName">
            資格情報コンテナーの名前
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した Azure key vault を取得します。
            </summary>
        <returns>
            資格情報コンテナー情報です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetResourceStorageConfigAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetResourceStorageConfigAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;" Usage="iVaultOperations.GetResourceStorageConfigAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            所属する資格情報コンテナーにリソース グループの名前
            </param>
        <param name="resourceName">
            資格情報コンテナーの名前
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースの記憶域構成をフェッチします。
            </summary>
        <returns>
            Get リソース記憶域構成の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync (int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync(int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListAsync(System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListAsync (top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="top">
            返される結果の最大数。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションに関連付けられているバックアップ資格情報コンテナーの情報を取得します。
            </summary>
        <returns>
            資格情報コンテナーの一覧
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync (string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync(string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListByResourceGroupAsync(System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupAsync : string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListByResourceGroupAsync (resourceGroupName, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            返される資格情報コンテナーのセットを制限するリソース グループの名前を指定する省略可能な引数。
            </param>
        <param name="top">
            返される結果の最大数。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループに関連付けられているバックアップ資格情報コンテナーの情報を取得します。
            </summary>
        <returns>
            資格情報コンテナーの一覧
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UpdateStorageTypeAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageTypeAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iVaultOperations.UpdateStorageTypeAsync (resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="updateVaultStorageTypeRequest">
            資格情報コンテナーの記憶域の種類の更新の要求
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UploadCertificateAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadCertificateAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;" Usage="iVaultOperations.UploadCertificateAsync (resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="certificateName">
            証明書の名前です。
            </param>
        <param name="vaultCredUploadCertRequest">
            証明書のパラメーターです。
            </param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            アップロードには、資格情報証明書が資格情報コンテナーします。
            </summary>
        <returns>
            証明書の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>