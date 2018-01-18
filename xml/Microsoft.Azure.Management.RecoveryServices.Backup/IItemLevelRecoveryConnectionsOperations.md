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
            <span data-ttu-id="d7a1c-101">ItemLevelRecoveryConnectionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-101">ItemLevelRecoveryConnectionsOperations operations.</span></span>
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
            <span data-ttu-id="d7a1c-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d7a1c-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="d7a1c-104">バックアップされた項目に関連付けられたファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-104">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="d7a1c-105">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-105">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="d7a1c-106">項目の名前のファイルとフォルダーを復元するバックアップされます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-106">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="d7a1c-107">バックアップは、データの回復ポイントの ID を表します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-107">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="d7a1c-108">iSCSI 接続は、このバックアップ データのプロビジョニングされます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-108">iSCSI connection will be provisioned for this backed up data.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d7a1c-109">リソース ILR 要求</span><span class="sxs-lookup"><span data-stu-id="d7a1c-109">resource ILR request</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d7a1c-110">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-110">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d7a1c-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d7a1c-112">バックアップのデータへの iSCSI 接続を呼び出すスクリプトを準備します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-112">Provisions a script which invokes an iSCSI connection to the backup data.</span></span> <span data-ttu-id="d7a1c-113">このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-113">Executing this script opens a file explorer displaying all the recoverable files and folders.</span></span> <span data-ttu-id="d7a1c-114">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-114">This is an asynchronous operation.</span></span> <span data-ttu-id="d7a1c-115">プロビジョニングの状態を確認するには、GetProtectedItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-115">To know the status of provisioning, call GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d7a1c-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d7a1c-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-117">Thrown when a required parameter is null</span></span>
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
            <span data-ttu-id="d7a1c-118">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-118">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d7a1c-119">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-119">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="d7a1c-120">バックアップされた項目に関連付けられたファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-120">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="d7a1c-121">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-121">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="d7a1c-122">項目の名前のファイルとフォルダーを復元するバックアップされます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-122">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="d7a1c-123">バックアップは、データの回復ポイントの ID を表します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-123">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="d7a1c-124">このバックアップ データの iSCSI 接続は取り消されます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-124">iSCSI connection will be revoked for this backed up data.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d7a1c-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d7a1c-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d7a1c-127">スクリプトをダウンロードするために使用する iSCSI 接続を取り消します。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-127">Revokes an iSCSI connection which can be used to download a script.</span></span>
            <span data-ttu-id="d7a1c-128">このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-128">Executing this script opens a file explorer displaying all recoverable files and folders.</span></span> <span data-ttu-id="d7a1c-129">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-129">This is an asynchronous operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d7a1c-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d7a1c-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d7a1c-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>