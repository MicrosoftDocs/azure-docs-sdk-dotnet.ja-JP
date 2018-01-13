<Type Name="IBackupPolicyOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations">
  <TypeSignature Language="C#" Value="public interface IBackupPolicyOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupPolicyOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupPolicyOperations" />
  <TypeSignature Language="F#" Value="type IBackupPolicyOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="144da-101">バックアップ ポリシーに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="144da-101">All Operations related to Backup policies</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.BeginCreatingBackupPolicyAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreatingBackupPolicyAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupPolicyOperations.BeginCreatingBackupPolicyAsync (deviceId, backupPolicy, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-102">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-102">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="144da-103">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="144da-103">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-104">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-104">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="144da-106">BeginCreatingBackupPolicy 操作は、特定のスケジュールを指定したこのボリュームの新しいバックアップ ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="144da-106">The BeginCreatingBackupPolicy operation creates a new backup policy for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="144da-107">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="144da-107">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.BeginDeletingAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeletingAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupPolicyOperations.BeginDeletingAsync (deviceId, policyId, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-108">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-108">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="144da-109">削除するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="144da-109">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-110">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-110">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="144da-112">提供される policyId によって表されるバックアップ ポリシーの削除を開始します。</span><span class="sxs-lookup"><span data-stu-id="144da-112">Begin deleting a backup policy represented by the policyId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="144da-113">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="144da-113">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.BeginUpdatingBackupPolicyAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdatingBackupPolicyAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupPolicyOperations.BeginUpdatingBackupPolicyAsync (deviceId, policyId, policyInfo, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-114">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-114">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="144da-115">更新するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="144da-115">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="144da-116">パラメーターは、バックアップ ポリシーの更新操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="144da-116">Parameters supplied to the Update Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-117">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="144da-119">BeginUpdatingBackupPolicy 操作では、指定されたスケジュールで指定したこのボリュームの policyId によって表されるバックアップ ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="144da-119">The BeginUpdatingBackupPolicy operation updates a backup policy represented by policyId for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="144da-120">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="144da-120">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.CreateAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupPolicyOperations.CreateAsync (deviceId, backupPolicy, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-121">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-121">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="144da-122">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="144da-122">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-123">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-123">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-124">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="144da-125">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="144da-125">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.DeleteAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupPolicyOperations.DeleteAsync (deviceId, policyId, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-126">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-126">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="144da-127">削除するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="144da-127">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-128">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-128">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-129">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="144da-130">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="144da-130">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync (string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync(string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.GetBackupPolicyDetailsByNameAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBackupPolicyDetailsByNameAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;" Usage="iBackupPolicyOperations.GetBackupPolicyDetailsByNameAsync (deviceId, policyName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-131">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-131">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="144da-132">バックアップ ポリシーの詳細をフェッチするポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="144da-132">The name of the policy to fetch backup policy details by.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-133">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-133">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-134">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="144da-135">バックアップ ポリシーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="144da-135">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.ListAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;" Usage="iBackupPolicyOperations.ListAsync (deviceId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-136">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-136">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-137">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-137">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-138">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="144da-139">バックアップ ポリシーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="144da-139">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.UpdateAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupPolicyOperations.UpdateAsync (deviceId, policyId, policyInfo, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="144da-140">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="144da-140">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="144da-141">更新するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="144da-141">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="144da-142">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="144da-142">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="144da-143">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="144da-143">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="144da-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="144da-144">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="144da-145">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="144da-145">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>