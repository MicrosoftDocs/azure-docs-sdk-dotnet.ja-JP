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
            <span data-ttu-id="1ec53-101">BackupsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="1ec53-101">BackupsOperations operations.</span></span>
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
            <span data-ttu-id="1ec53-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1ec53-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1ec53-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="1ec53-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="1ec53-104">バックアップ項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1ec53-104">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="1ec53-105">バックアップ アイテムに関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="1ec53-105">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="1ec53-106">どのバックアップ ニーズをトリガーするためのバックアップ アイテムです。</span><span class="sxs-lookup"><span data-stu-id="1ec53-106">Backup item for which backup needs to be triggered.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1ec53-107">バックアップのリソース要求</span><span class="sxs-lookup"><span data-stu-id="1ec53-107">resource backup request</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1ec53-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1ec53-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ec53-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1ec53-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ec53-110">指定のバックアップ項目のバックアップをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="1ec53-110">Triggers backup for specified backed up item.</span></span> <span data-ttu-id="1ec53-111">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="1ec53-111">This is an asynchronous operation.</span></span> <span data-ttu-id="1ec53-112">操作の状態を確認するには、GetProtectedItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="1ec53-112">To know the status of the operation, call GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1ec53-113">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1ec53-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1ec53-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1ec53-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>