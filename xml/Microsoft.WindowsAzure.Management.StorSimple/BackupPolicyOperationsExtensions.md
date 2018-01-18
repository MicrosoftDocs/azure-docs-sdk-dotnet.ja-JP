<Type Name="BackupPolicyOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupPolicyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupPolicyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupPolicyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupPolicyOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8ab4c-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="8ab4c-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackupPolicy">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackupPolicy (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackupPolicy(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicy(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicy (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-102">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-103">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-103">Required.</span></span> <span data-ttu-id="8ab4c-104">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-104">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="8ab4c-105">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-105">Required.</span></span> <span data-ttu-id="8ab4c-106">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-106">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-107">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-107">Required.</span></span> <span data-ttu-id="8ab4c-108">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ab4c-109">BeginCreatingBackupPolicy 操作は、特定のスケジュールを指定したこのボリュームの新しいバックアップ ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-109">The BeginCreatingBackupPolicy operation creates a new backup policy for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8ab4c-110">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="8ab4c-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicyAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupPolicyAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicyAsync (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-111">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-112">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-112">Required.</span></span> <span data-ttu-id="8ab4c-113">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-113">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="8ab4c-114">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-114">Required.</span></span> <span data-ttu-id="8ab4c-115">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-115">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-116">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-116">Required.</span></span> <span data-ttu-id="8ab4c-117">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ab4c-118">BeginCreatingBackupPolicy 操作は、特定のスケジュールを指定したこのボリュームの新しいバックアップ ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-118">The BeginCreatingBackupPolicy operation creates a new backup policy for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8ab4c-119">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="8ab4c-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeleting (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-120">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-121">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-121">Required.</span></span> <span data-ttu-id="8ab4c-122">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-122">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-123">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-123">Required.</span></span> <span data-ttu-id="8ab4c-124">削除するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-124">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-125">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-125">Required.</span></span> <span data-ttu-id="8ab4c-126">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ab4c-127">提供される policyId によって表されるバックアップ ポリシーの削除を開始します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-127">Begin deleting a backup policy represented by the policyId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8ab4c-128">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="8ab4c-128">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeletingAsync (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-129">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-129">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-130">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-130">Required.</span></span> <span data-ttu-id="8ab4c-131">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-131">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-132">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-132">Required.</span></span> <span data-ttu-id="8ab4c-133">削除するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-133">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-134">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-134">Required.</span></span> <span data-ttu-id="8ab4c-135">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-135">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ab4c-136">提供される policyId によって表されるバックアップ ポリシーの削除を開始します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-136">Begin deleting a backup policy represented by the policyId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8ab4c-137">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="8ab4c-137">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingBackupPolicy">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdatingBackupPolicy (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdatingBackupPolicy(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicy(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingBackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicy (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-138">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-138">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-139">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-139">Required.</span></span> <span data-ttu-id="8ab4c-140">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-140">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-141">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-141">Required.</span></span> <span data-ttu-id="8ab4c-142">更新するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-142">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="8ab4c-143">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-143">Required.</span></span> <span data-ttu-id="8ab4c-144">パラメーターは、バックアップ ポリシーの更新操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-144">Parameters supplied to the Update Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-145">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-145">Required.</span></span> <span data-ttu-id="8ab4c-146">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-146">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ab4c-147">BeginUpdatingBackupPolicy 操作では、指定されたスケジュールで指定したこのボリュームの policyId によって表されるバックアップ ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-147">The BeginUpdatingBackupPolicy operation updates a backup policy represented by policyId for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8ab4c-148">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="8ab4c-148">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicyAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingBackupPolicyAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicyAsync (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-149">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-149">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-150">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-150">Required.</span></span> <span data-ttu-id="8ab4c-151">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-151">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-152">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-152">Required.</span></span> <span data-ttu-id="8ab4c-153">更新するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-153">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="8ab4c-154">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-154">Required.</span></span> <span data-ttu-id="8ab4c-155">パラメーターは、バックアップ ポリシーの更新操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-155">Parameters supplied to the Update Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-156">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-156">Required.</span></span> <span data-ttu-id="8ab4c-157">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-157">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ab4c-158">BeginUpdatingBackupPolicy 操作では、指定されたスケジュールで指定したこのボリュームの policyId によって表されるバックアップ ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-158">The BeginUpdatingBackupPolicy operation updates a backup policy represented by policyId for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8ab4c-159">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="8ab4c-159">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Create (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-160">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-160">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-161">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-161">Required.</span></span> <span data-ttu-id="8ab4c-162">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-162">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="8ab4c-163">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-163">Required.</span></span> <span data-ttu-id="8ab4c-164">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-164">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-165">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-165">Required.</span></span> <span data-ttu-id="8ab4c-166">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-166">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-167">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="8ab4c-167">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.CreateAsync (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-168">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-168">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-169">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-169">Required.</span></span> <span data-ttu-id="8ab4c-170">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-170">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="8ab4c-171">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-171">Required.</span></span> <span data-ttu-id="8ab4c-172">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-172">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-173">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-173">Required.</span></span> <span data-ttu-id="8ab4c-174">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-174">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-175">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="8ab4c-175">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Delete (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-176">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-176">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-177">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-177">Required.</span></span> <span data-ttu-id="8ab4c-178">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-178">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-179">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-179">Required.</span></span> <span data-ttu-id="8ab4c-180">削除するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-180">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-181">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-181">Required.</span></span> <span data-ttu-id="8ab4c-182">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-182">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-183">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="8ab4c-183">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.DeleteAsync (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-184">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-184">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-185">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-185">Required.</span></span> <span data-ttu-id="8ab4c-186">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-186">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-187">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-187">Required.</span></span> <span data-ttu-id="8ab4c-188">削除するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-188">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-189">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-189">Required.</span></span> <span data-ttu-id="8ab4c-190">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-190">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-191">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="8ab4c-191">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByName">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse GetBackupPolicyDetailsByName (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse GetBackupPolicyDetailsByName(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByName(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetBackupPolicyDetailsByName : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByName (operations, deviceId, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-192">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-192">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-193">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-193">Required.</span></span> <span data-ttu-id="8ab4c-194">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-194">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="8ab4c-195">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-195">Required.</span></span> <span data-ttu-id="8ab4c-196">バックアップ ポリシーの詳細をフェッチするポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-196">The name of the policy to fetch backup policy details by.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-197">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-197">Required.</span></span> <span data-ttu-id="8ab4c-198">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-198">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-199">バックアップ ポリシーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-199">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByNameAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetBackupPolicyDetailsByNameAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByNameAsync (operations, deviceId, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-200">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-200">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-201">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-201">Required.</span></span> <span data-ttu-id="8ab4c-202">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-202">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="8ab4c-203">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-203">Required.</span></span> <span data-ttu-id="8ab4c-204">バックアップ ポリシーの詳細をフェッチするポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-204">The name of the policy to fetch backup policy details by.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-205">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-205">Required.</span></span> <span data-ttu-id="8ab4c-206">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-206">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-207">バックアップ ポリシーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-207">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.List (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-208">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-208">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-209">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-209">Required.</span></span> <span data-ttu-id="8ab4c-210">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-210">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-211">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-211">Required.</span></span> <span data-ttu-id="8ab4c-212">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-212">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-213">バックアップ ポリシーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-213">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.ListAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-214">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-214">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-215">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-215">Required.</span></span> <span data-ttu-id="8ab4c-216">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-216">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-217">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-217">Required.</span></span> <span data-ttu-id="8ab4c-218">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-218">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-219">バックアップ ポリシーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-219">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Update(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Update (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-220">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-220">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-221">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-221">Required.</span></span> <span data-ttu-id="8ab4c-222">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-222">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-223">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-223">Required.</span></span> <span data-ttu-id="8ab4c-224">更新するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-224">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="8ab4c-225">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-225">Required.</span></span> <span data-ttu-id="8ab4c-226">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-226">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-227">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-227">Required.</span></span> <span data-ttu-id="8ab4c-228">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-228">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-229">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="8ab4c-229">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.UpdateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.UpdateAsync (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ab4c-230">Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-230">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="8ab4c-231">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-231">Required.</span></span> <span data-ttu-id="8ab4c-232">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-232">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="8ab4c-233">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-233">Required.</span></span> <span data-ttu-id="8ab4c-234">更新するバックアップ ポリシーの ID。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-234">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="8ab4c-235">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-235">Required.</span></span> <span data-ttu-id="8ab4c-236">パラメーターは、バックアップ ポリシーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-236">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="8ab4c-237">必須。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-237">Required.</span></span> <span data-ttu-id="8ab4c-238">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ab4c-238">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="8ab4c-239">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="8ab4c-239">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>