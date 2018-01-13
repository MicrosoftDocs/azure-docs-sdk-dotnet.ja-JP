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
            <span data-ttu-id="7c34a-101">ItemLevelRecoveryConnectionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7c34a-101">Extension methods for ItemLevelRecoveryConnectionsOperations.</span></span>
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
            <span data-ttu-id="7c34a-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c34a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7c34a-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="7c34a-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c34a-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="7c34a-105">バックアップされた項目に関連付けられたファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-105">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="7c34a-106">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="7c34a-106">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="7c34a-107">項目の名前のファイルとフォルダーを復元するバックアップされます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-107">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="7c34a-108">バックアップは、データの回復ポイントの ID を表します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-108">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="7c34a-109">iSCSI 接続は、このバックアップ データのプロビジョニングされます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-109">iSCSI connection will be provisioned for this backed up data.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c34a-110">リソース ILR 要求</span><span class="sxs-lookup"><span data-stu-id="7c34a-110">resource ILR request</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c34a-111">バックアップのデータへの iSCSI 接続を呼び出すスクリプトを準備します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-111">Provisions a script which invokes an iSCSI connection to the backup data.</span></span>
            <span data-ttu-id="7c34a-112">このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-112">Executing this script opens a file explorer displaying all the recoverable files and folders.</span></span> <span data-ttu-id="7c34a-113">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-113">This is an asynchronous operation.</span></span> <span data-ttu-id="7c34a-114">プロビジョニングの状態を確認するには、GetProtectedItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-114">To know the status of provisioning, call GetProtectedItemOperationResult API.</span></span>
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
            <span data-ttu-id="7c34a-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c34a-115">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7c34a-116">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="7c34a-116">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c34a-117">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-117">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="7c34a-118">バックアップされた項目に関連付けられたファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-118">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="7c34a-119">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="7c34a-119">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="7c34a-120">項目の名前のファイルとフォルダーを復元するバックアップされます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-120">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="7c34a-121">バックアップは、データの回復ポイントの ID を表します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-121">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="7c34a-122">iSCSI 接続は、このバックアップ データのプロビジョニングされます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-122">iSCSI connection will be provisioned for this backed up data.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c34a-123">リソース ILR 要求</span><span class="sxs-lookup"><span data-stu-id="7c34a-123">resource ILR request</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c34a-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c34a-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c34a-125">バックアップのデータへの iSCSI 接続を呼び出すスクリプトを準備します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-125">Provisions a script which invokes an iSCSI connection to the backup data.</span></span>
            <span data-ttu-id="7c34a-126">このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-126">Executing this script opens a file explorer displaying all the recoverable files and folders.</span></span> <span data-ttu-id="7c34a-127">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-127">This is an asynchronous operation.</span></span> <span data-ttu-id="7c34a-128">プロビジョニングの状態を確認するには、GetProtectedItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-128">To know the status of provisioning, call GetProtectedItemOperationResult API.</span></span>
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
            <span data-ttu-id="7c34a-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c34a-129">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7c34a-130">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="7c34a-130">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c34a-131">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-131">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="7c34a-132">バックアップされた項目に関連付けられたファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-132">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="7c34a-133">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="7c34a-133">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="7c34a-134">項目の名前のファイルとフォルダーを復元するバックアップされます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-134">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="7c34a-135">バックアップは、データの回復ポイントの ID を表します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-135">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="7c34a-136">このバックアップ データの iSCSI 接続は取り消されます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-136">iSCSI connection will be revoked for this backed up data.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c34a-137">スクリプトをダウンロードするために使用する iSCSI 接続を取り消します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-137">Revokes an iSCSI connection which can be used to download a script.</span></span>
            <span data-ttu-id="7c34a-138">このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-138">Executing this script opens a file explorer displaying all recoverable files and folders.</span></span> <span data-ttu-id="7c34a-139">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-139">This is an asynchronous operation.</span></span>
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
            <span data-ttu-id="7c34a-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c34a-140">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7c34a-141">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="7c34a-141">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c34a-142">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-142">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="7c34a-143">バックアップされた項目に関連付けられたファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-143">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="7c34a-144">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="7c34a-144">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="7c34a-145">項目の名前のファイルとフォルダーを復元するバックアップされます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-145">Backed up item name whose files/folders are to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="7c34a-146">バックアップは、データの回復ポイントの ID を表します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-146">Recovery point ID which represents backed up data.</span></span> <span data-ttu-id="7c34a-147">このバックアップ データの iSCSI 接続は取り消されます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-147">iSCSI connection will be revoked for this backed up data.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c34a-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c34a-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c34a-149">スクリプトをダウンロードするために使用する iSCSI 接続を取り消します。</span><span class="sxs-lookup"><span data-stu-id="7c34a-149">Revokes an iSCSI connection which can be used to download a script.</span></span>
            <span data-ttu-id="7c34a-150">このスクリプトを実行すると、すべての回復可能なファイルとフォルダーを表示するファイル エクスプ ローラーが開きます。</span><span class="sxs-lookup"><span data-stu-id="7c34a-150">Executing this script opens a file explorer displaying all recoverable files and folders.</span></span> <span data-ttu-id="7c34a-151">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="7c34a-151">This is an asynchronous operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>