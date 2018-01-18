<Type Name="IBackupSchedulesOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations">
  <TypeSignature Language="C#" Value="public interface IBackupSchedulesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupSchedulesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupSchedulesOperations" />
  <TypeSignature Language="F#" Value="type IBackupSchedulesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c7d78-101">BackupSchedulesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c7d78-101">BackupSchedulesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="iBackupSchedulesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c7d78-102">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c7d78-102">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="c7d78-103">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="c7d78-103">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="c7d78-104">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="c7d78-104">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7d78-105">バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="c7d78-105">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7d78-106">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c7d78-106">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c7d78-107">管理者名</span><span class="sxs-lookup"><span data-stu-id="c7d78-107">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c7d78-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7d78-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7d78-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d78-110">作成するか、バックアップのスケジュールを更新します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-110">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c7d78-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c7d78-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c7d78-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupSchedulesOperations.BeginDeleteWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c7d78-114">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c7d78-114">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="c7d78-115">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="c7d78-115">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="c7d78-116">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="c7d78-116">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7d78-117">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c7d78-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c7d78-118">管理者名</span><span class="sxs-lookup"><span data-stu-id="c7d78-118">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c7d78-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7d78-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7d78-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d78-121">バックアップのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-121">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c7d78-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c7d78-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="iBackupSchedulesOperations.CreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c7d78-124">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c7d78-124">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="c7d78-125">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="c7d78-125">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="c7d78-126">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="c7d78-126">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7d78-127">バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="c7d78-127">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7d78-128">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c7d78-128">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c7d78-129">管理者名</span><span class="sxs-lookup"><span data-stu-id="c7d78-129">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c7d78-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7d78-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7d78-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d78-132">作成するか、バックアップのスケジュールを更新します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-132">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c7d78-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c7d78-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c7d78-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupSchedulesOperations.DeleteWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c7d78-136">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c7d78-136">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="c7d78-137">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="c7d78-137">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="c7d78-138">バックアップ スケジュールの名前です。</span><span class="sxs-lookup"><span data-stu-id="c7d78-138">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7d78-139">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c7d78-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c7d78-140">管理者名</span><span class="sxs-lookup"><span data-stu-id="c7d78-140">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c7d78-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7d78-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7d78-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d78-143">バックアップのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-143">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c7d78-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c7d78-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; GetWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; GetWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="iBackupSchedulesOperations.GetWithHttpMessagesAsync (deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c7d78-146">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c7d78-146">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="c7d78-147">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="c7d78-147">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="c7d78-148">フェッチするバックアップのスケジュールの名前</span><span class="sxs-lookup"><span data-stu-id="c7d78-148">The name of the backup schedule to be fetched</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7d78-149">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c7d78-149">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c7d78-150">管理者名</span><span class="sxs-lookup"><span data-stu-id="c7d78-150">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c7d78-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7d78-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7d78-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d78-153">指定したバックアップ スケジュールの名前のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-153">Gets the properties of the specified backup schedule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c7d78-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c7d78-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c7d78-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBackupPolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt; ListByBackupPolicyWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt; ListByBackupPolicyWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations.ListByBackupPolicyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBackupPolicyWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt;" Usage="iBackupSchedulesOperations.ListByBackupPolicyWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c7d78-157">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c7d78-157">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="c7d78-158">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="c7d78-158">The backup policy name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7d78-159">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c7d78-159">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c7d78-160">管理者名</span><span class="sxs-lookup"><span data-stu-id="c7d78-160">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c7d78-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7d78-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7d78-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d78-163">バックアップ ポリシー内のすべてのバックアップ スケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="c7d78-163">Gets all the backup schedules in a backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c7d78-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c7d78-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c7d78-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c7d78-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>