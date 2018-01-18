<Type Name="IJobScheduleOperations" FullName="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations">
  <TypeSignature Language="C#" Value="public interface IJobScheduleOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobScheduleOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobScheduleOperations" />
  <TypeSignature Language="F#" Value="type IJobScheduleOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7cce-101">JobScheduleOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="f7cce-101">JobScheduleOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt;" Usage="iJobScheduleOperations.AddWithHttpMessagesAsync (cloudJobSchedule, jobScheduleAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cloudJobSchedule" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" />
        <Parameter Name="jobScheduleAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cloudJobSchedule">
            <span data-ttu-id="f7cce-102">追加するジョブ スケジュールです。</span><span class="sxs-lookup"><span data-stu-id="f7cce-102">The job schedule to be added.</span></span>
            </param>
        <param name="jobScheduleAddOptions">
            <span data-ttu-id="f7cce-103">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-103">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-106">指定されたアカウントには、ジョブのスケジュールを追加します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-106">Adds a job schedule to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt;" Usage="iJobScheduleOperations.DeleteWithHttpMessagesAsync (jobScheduleId, jobScheduleDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-109">削除するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-109">The ID of the job schedule to delete.</span></span>
            </param>
        <param name="jobScheduleDeleteOptions">
            <span data-ttu-id="f7cce-110">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-110">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-111">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-111">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-113">指定されたアカウントからジョブのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-113">Deletes a job schedule from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f7cce-114">ジョブのスケジュールを削除するときにすべてのジョブとそのスケジュールの下にあるタスクも削除します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-114">When you delete a job schedule, this also deletes all jobs and tasks under that schedule.</span></span> <span data-ttu-id="f7cce-115">タスクが削除されると、すべてのファイルを作業ディレクトリをコンピューティング ノードにも削除 (保有期間は無視されます)。</span><span class="sxs-lookup"><span data-stu-id="f7cce-115">When tasks are deleted, all the files in their working directories on the compute nodes are also deleted (the retention period is ignored).</span></span> <span data-ttu-id="f7cce-116">ジョブ スケジュールの統計はアクセスできなくジョブのスケジュールが削除されると、アカウントの有効期間の統計情報に反映させるまだもします。</span><span class="sxs-lookup"><span data-stu-id="f7cce-116">The job schedule statistics are no longer accessible once the job schedule is deleted, though they are still counted towards account lifetime statistics.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.DisableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt;" Usage="iJobScheduleOperations.DisableWithHttpMessagesAsync (jobScheduleId, jobScheduleDisableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-119">無効にするジョブ スケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-119">The ID of the job schedule to disable.</span></span>
            </param>
        <param name="jobScheduleDisableOptions">
            <span data-ttu-id="f7cce-120">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-120">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-123">ジョブのスケジュールを無効にします。</span><span class="sxs-lookup"><span data-stu-id="f7cce-123">Disables a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f7cce-124">ジョブのスケジュールが再度有効にするまで、新しいジョブは作成されません。</span><span class="sxs-lookup"><span data-stu-id="f7cce-124">No new jobs will be created until the job schedule is enabled again.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.EnableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt;" Usage="iJobScheduleOperations.EnableWithHttpMessagesAsync (jobScheduleId, jobScheduleEnableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-127">有効にするジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-127">The ID of the job schedule to enable.</span></span>
            </param>
        <param name="jobScheduleEnableOptions">
            <span data-ttu-id="f7cce-128">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-128">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-131">ジョブのスケジュールを有効にします。</span><span class="sxs-lookup"><span data-stu-id="f7cce-131">Enables a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;bool, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt;" Usage="iJobScheduleOperations.ExistsWithHttpMessagesAsync (jobScheduleId, jobScheduleExistsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-134">確認するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-134">The ID of the job schedule which you want to check.</span></span>
            </param>
        <param name="jobScheduleExistsOptions">
            <span data-ttu-id="f7cce-135">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-135">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-138">指定されたジョブのスケジュールを確認します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-138">Checks the specified job schedule exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt;" Usage="iJobScheduleOperations.GetWithHttpMessagesAsync (jobScheduleId, jobScheduleGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-141">取得するジョブ スケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-141">The ID of the job schedule to get.</span></span>
            </param>
        <param name="jobScheduleGetOptions">
            <span data-ttu-id="f7cce-142">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-142">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-145">指定されたジョブのスケジュールに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-145">Gets information about the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-146">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f7cce-147">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-147">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-148">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;" Usage="iJobScheduleOperations.ListNextWithHttpMessagesAsync (nextPageLink, jobScheduleListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobScheduleListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f7cce-149">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f7cce-149">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobScheduleListNextOptions">
            <span data-ttu-id="f7cce-150">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-150">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-153">指定されたアカウント内のジョブ スケジュールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-153">Lists all of the job schedules in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f7cce-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;" Usage="iJobScheduleOperations.ListWithHttpMessagesAsync (jobScheduleListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleListOptions">
            <span data-ttu-id="f7cce-157">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-157">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-158">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-158">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-160">指定されたアカウント内のジョブ スケジュールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-160">Lists all of the job schedules in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-161">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f7cce-162">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-162">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PatchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt;" Usage="iJobScheduleOperations.PatchWithHttpMessagesAsync (jobScheduleId, jobSchedulePatchParameter, jobSchedulePatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobSchedulePatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
        <Parameter Name="jobSchedulePatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-164">更新するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-164">The ID of the job schedule to update.</span></span>
            </param>
        <param name="jobSchedulePatchParameter">
            <span data-ttu-id="f7cce-165">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f7cce-165">The parameters for the request.</span></span>
            </param>
        <param name="jobSchedulePatchOptions">
            <span data-ttu-id="f7cce-166">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-166">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-169">指定したジョブ スケジュールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-169">Updates the properties of the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f7cce-170">これには、要求で指定されたジョブのスケジュールのプロパティのみが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-170">This replaces only the job schedule properties specified in the request.</span></span> <span data-ttu-id="f7cce-171">たとえば、スケジュールのプロパティがこの要求に指定されていない場合、Batch service、既存のスケジュールは保持します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-171">For example, if the schedule property is not specified with this request, then the Batch service will keep the existing schedule.</span></span> <span data-ttu-id="f7cce-172">ジョブに変更が行われた後、更新プログラムが; スケジュールによって作成された影響ジョブのみをスケジュールします。現在実行中のジョブは、影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="f7cce-172">Changes to a job schedule only impact jobs created by the schedule after the update has taken place; currently running jobs are unaffected.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.TerminateWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt;" Usage="iJobScheduleOperations.TerminateWithHttpMessagesAsync (jobScheduleId, jobScheduleTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-175">終了するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-175">The ID of the job schedule to terminates.</span></span>
            </param>
        <param name="jobScheduleTerminateOptions">
            <span data-ttu-id="f7cce-176">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-176">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-179">ジョブのスケジュールを終了します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-179">Terminates a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobScheduleOperations.UpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt;" Usage="iJobScheduleOperations.UpdateWithHttpMessagesAsync (jobScheduleId, jobScheduleUpdateParameter, jobScheduleUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" />
        <Parameter Name="jobScheduleUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="f7cce-182">更新するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="f7cce-182">The ID of the job schedule to update.</span></span>
            </param>
        <param name="jobScheduleUpdateParameter">
            <span data-ttu-id="f7cce-183">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f7cce-183">The parameters for the request.</span></span>
            </param>
        <param name="jobScheduleUpdateOptions">
            <span data-ttu-id="f7cce-184">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f7cce-184">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7cce-185">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7cce-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7cce-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7cce-187">指定したジョブ スケジュールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-187">Updates the properties of the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f7cce-188">これには、ジョブ スケジュールの更新可能なプロパティがすべて完全に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-188">This fully replaces all the updateable properties of the job schedule.</span></span> <span data-ttu-id="f7cce-189">たとえば、この要求には、スケジュールのプロパティが指定されていない、バッチ サービスは、既存のスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="f7cce-189">For example, if the schedule property is not specified with this request, then the Batch service will remove the existing schedule.</span></span> <span data-ttu-id="f7cce-190">ジョブに変更が行われた後、更新プログラムが; スケジュールによって作成された影響ジョブのみをスケジュールします。現在実行中のジョブは、影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="f7cce-190">Changes to a job schedule only impact jobs created by the schedule after the update has taken place; currently running jobs are unaffected.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f7cce-191">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-191">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7cce-192">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7cce-192">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>