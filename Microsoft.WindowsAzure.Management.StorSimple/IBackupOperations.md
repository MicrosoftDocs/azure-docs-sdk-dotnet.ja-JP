<Type Name="IBackupOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations">
  <TypeSignature Language="C#" Value="public interface IBackupOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupOperations" />
  <TypeSignature Language="F#" Value="type IBackupOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0aca1-101">バックアップに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="0aca1-101">All Operations related to Backup</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.BeginCreatingBackupAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreatingBackupAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupOperations.BeginCreatingBackupAsync (deviceId, policyId, backupRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="0aca1-102">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="0aca1-102">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="0aca1-103">呼び出しの行われたポリシーの id。</span><span class="sxs-lookup"><span data-stu-id="0aca1-103">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="0aca1-104">パラメーターは、バックアップを開始操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-104">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="0aca1-105">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aca1-105">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0aca1-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0aca1-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0aca1-107">PolicyId と backupRequest 指定のバックアップ操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-107">Begin a backup operation for the policyId and backupRequest specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0aca1-108">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="0aca1-108">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.BeginDeletingAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeletingAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupOperations.BeginDeletingAsync (deviceId, backupSetId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="0aca1-109">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="0aca1-109">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="0aca1-110">バックアップ セットの ID を削除します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-110">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="0aca1-111">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aca1-111">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0aca1-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0aca1-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0aca1-113">指定された backSetId によって表されるバックアップ セットの削除を開始します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-113">Begin deleting a backup set represented by the backSetId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0aca1-114">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="0aca1-114">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoringAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.BeginRestoringAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRestoringAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupOperations.BeginRestoringAsync (deviceId, backupDetailsForRestore, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="0aca1-115">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="0aca1-115">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="0aca1-116">復元するバックアップの詳細。</span><span class="sxs-lookup"><span data-stu-id="0aca1-116">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="0aca1-117">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aca1-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0aca1-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0aca1-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0aca1-119">バックアップ セットの復元を開始します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-119">Begin restoring a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0aca1-120">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="0aca1-120">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.CreateAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupOperations.CreateAsync (deviceId, policyId, backupRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="0aca1-121">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="0aca1-121">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="0aca1-122">呼び出しの行われたポリシーの id。</span><span class="sxs-lookup"><span data-stu-id="0aca1-122">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="0aca1-123">パラメーターは、バックアップを開始操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-123">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="0aca1-124">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aca1-124">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0aca1-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0aca1-125">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="0aca1-126">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="0aca1-126">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.DeleteAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupOperations.DeleteAsync (deviceId, backupSetId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="0aca1-127">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="0aca1-127">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="0aca1-128">バックアップ セットの ID を削除します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-128">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="0aca1-129">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aca1-129">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0aca1-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0aca1-130">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="0aca1-131">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="0aca1-131">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync (string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync(string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.GetAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * string * string * string * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;" Usage="iBackupOperations.GetAsync (deviceId, filterType, isAllSelected, filterValue, startTime, endTime, skip, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="filterType" Type="System.String" />
        <Parameter Name="isAllSelected" Type="System.String" />
        <Parameter Name="filterValue" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="0aca1-132">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="0aca1-132">The device id for which the call will be made.</span></span>
            </param>
        <param name="filterType">
            <span data-ttu-id="0aca1-133">場合 isAllSelected = true の場合、そのボリュームまたは BackupPolicy をここで指定</span><span class="sxs-lookup"><span data-stu-id="0aca1-133">If isAllSelected = true, then specify Volume or BackupPolicy here</span></span>
            </param>
        <param name="isAllSelected">
            <span data-ttu-id="0aca1-134">ボリュームまたは BackupPolicy またはその両方を取得するには</span><span class="sxs-lookup"><span data-stu-id="0aca1-134">To retrieve Volume or BackupPolicy or both</span></span>
            </param>
        <param name="filterValue">
            <span data-ttu-id="0aca1-135">場合 isAllSelected = true、VolumeId または BackupPolicy をここで指定し、</span><span class="sxs-lookup"><span data-stu-id="0aca1-135">If isAllSelected = true then specify VolumeId or BackupPolicy here</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="0aca1-136">バックアップ セットをフィルター処理の開始時刻</span><span class="sxs-lookup"><span data-stu-id="0aca1-136">StartTime for filtering BackupSets</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="0aca1-137">バックアップ セットをフィルター処理の終了時刻</span><span class="sxs-lookup"><span data-stu-id="0aca1-137">EndTime for filtering BackupSets</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="0aca1-138">改ページの一部としてスキップする要素の数</span><span class="sxs-lookup"><span data-stu-id="0aca1-138">Number of elements to be skipped as part of pagination</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="0aca1-139">現在のページで取得する要素の数</span><span class="sxs-lookup"><span data-stu-id="0aca1-139">Number of elements to retrieve in the current page</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="0aca1-140">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aca1-140">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0aca1-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0aca1-141">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="0aca1-142">バックアップ セットの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="0aca1-142">The response model for the list of BackupSets.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.RestoreAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupOperations.RestoreAsync (deviceId, backupDetailsForRestore, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="0aca1-143">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="0aca1-143">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="0aca1-144">復元するバックアップの詳細。</span><span class="sxs-lookup"><span data-stu-id="0aca1-144">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="0aca1-145">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aca1-145">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0aca1-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0aca1-146">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0aca1-147">バックアップ セットを復元します。</span><span class="sxs-lookup"><span data-stu-id="0aca1-147">Restore a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0aca1-148">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="0aca1-148">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>