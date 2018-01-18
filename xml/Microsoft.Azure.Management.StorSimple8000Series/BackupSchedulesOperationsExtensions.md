<Type Name="BackupSchedulesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupSchedulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupSchedulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupSchedulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupSchedulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80564-101">BackupSchedulesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="80564-101">Extension methods for BackupSchedulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, parameters As BackupSchedule, resourceGroupName As String, managerName As String) As BackupSchedule" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdate (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-103">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-103">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-104">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-104">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-105">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-105">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="80564-106">バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="80564-106">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-107">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-107">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-108">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-108">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-109">作成するか、バックアップのスケジュールを更新します。</span><span class="sxs-lookup"><span data-stu-id="80564-109">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-110">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-111">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-111">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-112">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-112">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-113">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-113">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="80564-114">バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="80564-114">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-115">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-116">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-116">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80564-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="80564-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-118">作成するか、バックアップのスケジュールを更新します。</span><span class="sxs-lookup"><span data-stu-id="80564-118">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDelete (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-119">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-120">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-120">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-121">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-121">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-122">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-122">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-123">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-123">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-124">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-124">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-125">バックアップのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="80564-125">Deletes the backup schedule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDeleteAsync (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-126">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-127">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-127">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-128">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-128">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-129">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-129">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-130">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-130">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-131">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-131">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80564-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="80564-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-133">バックアップのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="80564-133">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, parameters As BackupSchedule, resourceGroupName As String, managerName As String) As BackupSchedule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdate (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-134">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-135">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-135">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-136">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-136">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-137">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-137">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="80564-138">バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="80564-138">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-139">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-140">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-140">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-141">作成するか、バックアップのスケジュールを更新します。</span><span class="sxs-lookup"><span data-stu-id="80564-141">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdateAsync (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-142">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-143">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-143">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-144">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-144">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-145">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-145">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="80564-146">バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="80564-146">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-147">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-148">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-148">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80564-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="80564-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-150">作成するか、バックアップのスケジュールを更新します。</span><span class="sxs-lookup"><span data-stu-id="80564-150">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Delete (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-151">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-152">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-152">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-153">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-153">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-154">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-154">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-155">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-155">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-156">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-156">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-157">バックアップのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="80564-157">Deletes the backup schedule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.DeleteAsync (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-158">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-159">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-159">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-160">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-160">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-161">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="80564-161">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-162">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-163">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-163">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80564-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="80564-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-165">バックアップのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="80564-165">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule Get (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule Get(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, resourceGroupName As String, managerName As String) As BackupSchedule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Get (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-166">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-167">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-167">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-168">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-168">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-169">フェッチするバックアップのスケジュールの名前</span><span class="sxs-lookup"><span data-stu-id="80564-169">The name of the backup schedule to be fetched</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-170">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-170">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-171">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-171">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-172">指定したバックアップ スケジュールの名前のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="80564-172">Gets the properties of the specified backup schedule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.GetAsync (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-173">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-174">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-174">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-175">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-175">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="80564-176">フェッチするバックアップのスケジュールの名前</span><span class="sxs-lookup"><span data-stu-id="80564-176">The name of the backup schedule to be fetched</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-177">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-177">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-178">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-178">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80564-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="80564-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-180">指定したバックアップ スケジュールの名前のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="80564-180">Gets the properties of the specified backup schedule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBackupPolicy">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; ListByBackupPolicy (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; ListByBackupPolicy(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicy(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBackupPolicy (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of BackupSchedule)" />
      <MemberSignature Language="F#" Value="static member ListByBackupPolicy : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicy (operations, deviceName, backupPolicyName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-181">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-182">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-182">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-183">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-183">The backup policy name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-184">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-184">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-185">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-185">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-186">バックアップ ポリシー内のすべてのバックアップ スケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="80564-186">Gets all the backup schedules in a backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; ListByBackupPolicyAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; ListByBackupPolicyAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicyAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBackupPolicyAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicyAsync (operations, deviceName, backupPolicyName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;ListByBackupPolicyAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="80564-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="80564-187">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="80564-188">デバイス名</span><span class="sxs-lookup"><span data-stu-id="80564-188">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="80564-189">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="80564-189">The backup policy name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="80564-190">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="80564-190">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="80564-191">管理者名</span><span class="sxs-lookup"><span data-stu-id="80564-191">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80564-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="80564-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80564-193">バックアップ ポリシー内のすべてのバックアップ スケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="80564-193">Gets all the backup schedules in a backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>