<Type Name="IBackupPoliciesOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations">
  <TypeSignature Language="C#" Value="public interface IBackupPoliciesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupPoliciesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupPoliciesOperations" />
  <TypeSignature Language="F#" Value="type IBackupPoliciesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b43f5-101">BackupPoliciesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b43f5-101">BackupPoliciesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackupNowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BackupNowWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BackupNowWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BackupNowWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupNowWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.BackupNowWithHttpMessagesAsync (deviceName, backupPolicyName, backupType, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b43f5-102">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-102">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b43f5-103">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="b43f5-103">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="b43f5-104">バックアップの種類。</span><span class="sxs-lookup"><span data-stu-id="b43f5-104">The backup Type.</span></span> <span data-ttu-id="b43f5-105">これには、cloudSnapshot または localSnapshot を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-105">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-106">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-106">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-107">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-107">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-110">バックアップ ポリシーを今すぐバックアップします。</span><span class="sxs-lookup"><span data-stu-id="b43f5-110">Backup the backup policy now.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginBackupNowWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginBackupNowWithHttpMessagesAsync (string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginBackupNowWithHttpMessagesAsync(string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BeginBackupNowWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginBackupNowWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.BeginBackupNowWithHttpMessagesAsync (deviceName, backupPolicyName, backupType, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b43f5-113">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-113">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b43f5-114">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="b43f5-114">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="b43f5-115">バックアップの種類。</span><span class="sxs-lookup"><span data-stu-id="b43f5-115">The backup Type.</span></span> <span data-ttu-id="b43f5-116">これには、cloudSnapshot または localSnapshot を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-116">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-117">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-118">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-118">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-121">バックアップ ポリシーを今すぐバックアップします。</span><span class="sxs-lookup"><span data-stu-id="b43f5-121">Backup the backup policy now.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;" Usage="iBackupPoliciesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b43f5-124">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-124">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b43f5-125">作成または更新するバックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="b43f5-125">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b43f5-126">バックアップ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="b43f5-126">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-127">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-127">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-128">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-128">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-131">作成するか、バックアップ ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-131">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b43f5-133">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-133">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-134">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-134">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.BeginDeleteWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b43f5-135">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-135">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b43f5-136">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="b43f5-136">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-137">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-137">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-138">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-138">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-141">バックアップ ポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-141">Deletes the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-143">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;" Usage="iBackupPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync (deviceName, backupPolicyName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b43f5-144">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-144">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b43f5-145">作成または更新するバックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="b43f5-145">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b43f5-146">バックアップ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="b43f5-146">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-147">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-148">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-148">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-149">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-149">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-151">作成するか、バックアップ ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-151">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b43f5-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iBackupPoliciesOperations.DeleteWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b43f5-155">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-155">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b43f5-156">バックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="b43f5-156">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-157">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-157">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-158">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-158">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-161">バックアップ ポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-161">Deletes the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-162">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; GetWithHttpMessagesAsync (string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; GetWithHttpMessagesAsync(string deviceName, string backupPolicyName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;" Usage="iBackupPoliciesOperations.GetWithHttpMessagesAsync (deviceName, backupPolicyName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;</ReturnType>
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
            <span data-ttu-id="b43f5-164">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-164">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="b43f5-165">フェッチするバックアップ ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="b43f5-165">The name of backup policy to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-166">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-167">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-167">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-168">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-168">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-170">指定したバックアップ ポリシー名のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-170">Gets the properties of the specified backup policy name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-171">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b43f5-172">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-172">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-173">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations.ListByDeviceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDeviceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt;" Usage="iBackupPoliciesOperations.ListByDeviceWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="b43f5-174">デバイス名</span><span class="sxs-lookup"><span data-stu-id="b43f5-174">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b43f5-175">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="b43f5-175">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="b43f5-176">管理者名</span><span class="sxs-lookup"><span data-stu-id="b43f5-176">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b43f5-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b43f5-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b43f5-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b43f5-179">デバイスのすべてのバックアップ ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b43f5-179">Gets all the backup policies in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b43f5-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b43f5-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b43f5-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b43f5-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>