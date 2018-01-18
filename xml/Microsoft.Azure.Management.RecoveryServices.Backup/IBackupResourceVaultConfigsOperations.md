<Type Name="IBackupResourceVaultConfigsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations">
  <TypeSignature Language="C#" Value="public interface IBackupResourceVaultConfigsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupResourceVaultConfigsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupResourceVaultConfigsOperations" />
  <TypeSignature Language="F#" Value="type IBackupResourceVaultConfigsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81c14-101">BackupResourceVaultConfigsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="81c14-101">BackupResourceVaultConfigsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt;" Usage="iBackupResourceVaultConfigsOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="81c14-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="81c14-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81c14-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="81c14-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81c14-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81c14-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81c14-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81c14-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81c14-106">リソース資格情報コンテナーの構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="81c14-106">Fetches resource vault config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81c14-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81c14-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="81c14-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81c14-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81c14-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81c14-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt; UpdateWithHttpMessagesAsync (string vaultName, string resourceGroupName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt; UpdateWithHttpMessagesAsync(string vaultName, string resourceGroupName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceVaultConfigsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt;" Usage="iBackupResourceVaultConfigsOperations.UpdateWithHttpMessagesAsync (vaultName, resourceGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="81c14-110">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="81c14-110">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="81c14-111">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="81c14-111">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="81c14-112">リソース構成の要求</span><span class="sxs-lookup"><span data-stu-id="81c14-112">resource config request</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="81c14-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="81c14-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81c14-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="81c14-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81c14-115">更新プログラムには、セキュリティ構成が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="81c14-115">Updates vault security config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="81c14-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81c14-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="81c14-117">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81c14-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81c14-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81c14-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>