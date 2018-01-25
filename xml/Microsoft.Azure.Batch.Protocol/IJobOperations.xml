<Type Name="IJobOperations" FullName="Microsoft.Azure.Batch.Protocol.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8e287-101">JobOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="8e287-101">JobOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt;" Usage="iJobOperations.AddWithHttpMessagesAsync (job, jobAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="job">
            <span data-ttu-id="8e287-102">追加するジョブです。</span><span class="sxs-lookup"><span data-stu-id="8e287-102">The job to be added.</span></span>
            </param>
        <param name="jobAddOptions">
            <span data-ttu-id="8e287-103">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-103">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-106">指定されたアカウントに、ジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="8e287-106">Adds a job to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-107">バッチ サービスでは、ジョブの一部として行われる処理を制御する 2 つの方法をサポートします。</span><span class="sxs-lookup"><span data-stu-id="8e287-107">The Batch service supports two ways to control the work done as part of a job.</span></span> <span data-ttu-id="8e287-108">最初の方法では、ユーザーは、ジョブ マネージャー タスクを指定します。</span><span class="sxs-lookup"><span data-stu-id="8e287-108">In the first approach, the user specifies a Job Manager task.</span></span> <span data-ttu-id="8e287-109">バッチ サービスは、ジョブを開始する準備ができたときに、このタスクを起動します。</span><span class="sxs-lookup"><span data-stu-id="8e287-109">The Batch service launches this task when it is ready to start the job.</span></span> <span data-ttu-id="8e287-110">ジョブ マネージャー タスクは、タスクの Api を使用して、このジョブで実行される他のすべてのタスクを制御します。</span><span class="sxs-lookup"><span data-stu-id="8e287-110">The Job Manager task controls all other tasks that run under this job, by using the Task APIs.</span></span> <span data-ttu-id="8e287-111">2 番目の方法で、ユーザーは直接タスク Api を使用してアクティブなジョブのタスクの実行を制御します。</span><span class="sxs-lookup"><span data-stu-id="8e287-111">In the second approach, the user directly controls the execution of tasks under an active job, by using the Task APIs.</span></span> <span data-ttu-id="8e287-112">注意してください。 ジョブの名前を付けるときは、ユーザー名またはシークレット プロジェクト名などの機密情報が含まれないようにします。</span><span class="sxs-lookup"><span data-stu-id="8e287-112">Also note: when naming jobs, avoid including sensitive information such as user names or secret project names.</span></span> <span data-ttu-id="8e287-113">この情報は、Microsoft サポート エンジニアにアクセスできる製品利用統計情報ログに表示可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8e287-113">This information may appear in telemetry logs accessible to Microsoft Support engineers.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-114">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt;" Usage="iJobOperations.DeleteWithHttpMessagesAsync (jobId, jobDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-116">削除するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-116">The ID of the job to delete.</span></span>
            </param>
        <param name="jobDeleteOptions">
            <span data-ttu-id="8e287-117">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-117">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-120">ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="8e287-120">Deletes a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-121">ジョブを削除すると、そのジョブの一部であるすべてのタスクとすべてのジョブの統計も削除されます。</span><span class="sxs-lookup"><span data-stu-id="8e287-121">Deleting a job also deletes all tasks that are part of that job, and all job statistics.</span></span> <span data-ttu-id="8e287-122">タスクのデータの保有期間も上書きされます。つまり、ジョブにコンピューティング ノードで保持されているタスクが含まれている場合、バッチ サービスをそれらのタスクの作業ディレクトリとそのすべてのコンテンツを削除します。</span><span class="sxs-lookup"><span data-stu-id="8e287-122">This also overrides the retention period for task data; that is, if the job contains tasks which are still retained on compute nodes, the Batch services deletes those tasks' working directories and all their contents.</span></span>  <span data-ttu-id="8e287-123">ジョブの削除要求を受信すると、バッチ サービスは、削除の状態にジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="8e287-123">When a Delete Job request is received, the Batch service sets the job to the deleting state.</span></span> <span data-ttu-id="8e287-124">ジョブの状態を削除するのには上のすべての更新操作は、追加情報をジョブが削除されていることを示すステータス コード 409 (Conflict) で失敗します。</span><span class="sxs-lookup"><span data-stu-id="8e287-124">All update operations on a job that is in deleting state will fail with status code 409 (Conflict), with additional information indicating that the job is being deleted.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync(string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.DisableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt;" Usage="iJobOperations.DisableWithHttpMessagesAsync (jobId, disableTasks, jobDisableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-127">無効にするジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-127">The ID of the job to disable.</span></span>
            </param>
        <param name="disableTasks">
            <span data-ttu-id="8e287-128">ジョブに関連付けられているアクティブなタスクを行うには何か。</span><span class="sxs-lookup"><span data-stu-id="8e287-128">What to do with active tasks associated with the job.</span></span> <span data-ttu-id="8e287-129">使用可能な値が含まれます: 'キューに再登録'、'終了'、'待機'</span><span class="sxs-lookup"><span data-stu-id="8e287-129">Possible values include: 'requeue', 'terminate', 'wait'</span></span>
            </param>
        <param name="jobDisableOptions">
            <span data-ttu-id="8e287-130">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-130">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-133">新しいタスクの実行を妨げて、指定されたジョブを無効にします。</span><span class="sxs-lookup"><span data-stu-id="8e287-133">Disables the specified job, preventing new tasks from running.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-134">すぐに、Batch Service はジョブを無効化の状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="8e287-134">The Batch Service immediately moves the job to the disabling state.</span></span>
            <span data-ttu-id="8e287-135">バッチは、この disableTasks パラメーターを使用して、ジョブの現在実行中のタスクを行うには何かを判断します。</span><span class="sxs-lookup"><span data-stu-id="8e287-135">Batch then uses the disableTasks parameter to determine what to do with the currently running tasks of the job.</span></span> <span data-ttu-id="8e287-136">ジョブ状態のまま残す無効にすると無効化操作が完了し、すべてのタスクが処理済み disableTasks オプション; に基づいてまでジョブは、無効の状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="8e287-136">The job remains in the disabling state until the disable operation is completed and all tasks have been dealt with according to the disableTasks option; the job then moves to the disabled state.</span></span> <span data-ttu-id="8e287-137">コンソール アプリケーションは、アクティブな状態に戻るまで、ジョブの下で、新しいタスクは開始されません。</span><span class="sxs-lookup"><span data-stu-id="8e287-137">No new tasks are started under the job until it moves back to active state.</span></span> <span data-ttu-id="8e287-138">Active 以外の任意の状態になっているジョブを無効にしようとすると、無効化または無効にされた、要求が失敗したステータス コード 409 でします。</span><span class="sxs-lookup"><span data-stu-id="8e287-138">If you try to disable a job that is in any state other than active, disabling, or disabled, the request fails with status code 409.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.EnableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt;" Usage="iJobOperations.EnableWithHttpMessagesAsync (jobId, jobEnableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-141">有効にするジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-141">The ID of the job to enable.</span></span>
            </param>
        <param name="jobEnableOptions">
            <span data-ttu-id="8e287-142">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-142">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-145">新しいタスクの実行を許可する、指定されたジョブを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8e287-145">Enables the specified job, allowing new tasks to run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-146">この API を呼び出すときに、バッチ サービスは、有効にすると、状態を無効になっているジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="8e287-146">When you call this API, the Batch service sets a disabled job to the enabling state.</span></span> <span data-ttu-id="8e287-147">この後、ジョブはアクティブ状態、およびジョブの再開での新しいタスクのスケジュール に移動操作を完了すると、します。</span><span class="sxs-lookup"><span data-stu-id="8e287-147">After the this operation is completed, the job moves to the active state, and scheduling of new tasks under the job resumes.</span></span> <span data-ttu-id="8e287-148">バッチ サービスでは、7 日間を超えてアクティブ状態のままにして、タスクは許可されません。</span><span class="sxs-lookup"><span data-stu-id="8e287-148">The Batch service does not allow a task to remain in the active state for more than 7 days.</span></span> <span data-ttu-id="8e287-149">そのため、7 日以上前に追加されたアクティブなタスクを含むジョブを有効にすると、それらのタスクは実行されません。</span><span class="sxs-lookup"><span data-stu-id="8e287-149">Therefore, if you enable a job containing active tasks which were added more than 7 days ago, those tasks will not run.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-150">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.JobStatistics, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllLifetimeStatisticsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt;" Usage="iJobOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync (jobGetAllLifetimeStatisticsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobGetAllLifetimeStatisticsOptions">
            <span data-ttu-id="8e287-152">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-152">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-155">指定されたアカウント内のジョブのすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8e287-155">Gets lifetime summary statistics for all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-156">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。</span><span class="sxs-lookup"><span data-stu-id="8e287-156">Statistics are aggregated across all jobs that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-157">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-157">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-158">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-158">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-159">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt; GetTaskCountsWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskCounts, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt; GetTaskCountsWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetTaskCountsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTaskCountsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt;" Usage="iJobOperations.GetTaskCountsWithHttpMessagesAsync (jobId, jobGetTaskCountsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-160">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-160">The ID of the job.</span></span>
            </param>
        <param name="jobGetTaskCountsOptions">
            <span data-ttu-id="8e287-161">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-161">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-164">指定されたジョブのタスクの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="8e287-164">Gets the task counts for the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-165">タスクの数は、アクティブな実行中または完了したタスクの状態によって、タスクの数と、成功または失敗したタスクの数を提供します。</span><span class="sxs-lookup"><span data-stu-id="8e287-165">Task counts provide a count of the tasks by active, running or completed task state, and a count of tasks which succeeded or failed.</span></span> <span data-ttu-id="8e287-166">準備状態のタスクが実行中としてカウントされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-166">Tasks in the preparing state are counted as running.</span></span> <span data-ttu-id="8e287-167">ValidationStatus が検証済みでない場合、Batch サービスがされていませんリスト タスク API で報告されるタスクの状態に対して状態の数を確認できません。</span><span class="sxs-lookup"><span data-stu-id="8e287-167">If the validationStatus is unvalidated, then the Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span> <span data-ttu-id="8e287-168">ジョブには、200,000 以上のタスクが含まれている場合に、validationStatus を検証できない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8e287-168">The validationStatus may be unvalidated if the job contains more than 200,000 tasks.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob,Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob, class Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob, Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt;" Usage="iJobOperations.GetWithHttpMessagesAsync (jobId, jobGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob,Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-172">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-172">The ID of the job.</span></span>
            </param>
        <param name="jobGetOptions">
            <span data-ttu-id="8e287-173">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-173">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-174">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-174">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-176">指定したジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8e287-176">Gets information about the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-177">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-177">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-178">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-178">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-179">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-179">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListFromJobScheduleNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromJobScheduleNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;" Usage="iJobOperations.ListFromJobScheduleNextWithHttpMessagesAsync (nextPageLink, jobListFromJobScheduleNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="8e287-180">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8e287-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            <span data-ttu-id="8e287-181">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-181">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-182">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-182">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-184">指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8e287-184">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-185">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-185">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-186">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-186">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-187">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-187">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListFromJobScheduleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromJobScheduleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;" Usage="iJobOperations.ListFromJobScheduleWithHttpMessagesAsync (jobScheduleId, jobListFromJobScheduleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            <span data-ttu-id="8e287-188">ジョブの一覧を取得するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-188">The ID of the job schedule from which you want to get a list of jobs.</span></span>
            </param>
        <param name="jobListFromJobScheduleOptions">
            <span data-ttu-id="8e287-189">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-189">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-190">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-190">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-192">指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8e287-192">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-193">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-193">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-194">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-194">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" Usage="iJobOperations.ListNextWithHttpMessagesAsync (nextPageLink, jobListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="8e287-196">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8e287-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListNextOptions">
            <span data-ttu-id="8e287-197">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-197">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-198">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-198">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-200">指定されたアカウント内のジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8e287-200">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-201">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-201">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-202">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-202">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-203">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-203">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;" Usage="iJobOperations.ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync (nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="8e287-204">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8e287-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            <span data-ttu-id="8e287-205">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-205">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-206">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-206">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-208">ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8e287-208">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-209">この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。</span><span class="sxs-lookup"><span data-stu-id="8e287-209">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="8e287-210">これには、プールからからは削除されているノードが含まれます。</span><span class="sxs-lookup"><span data-stu-id="8e287-210">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="8e287-211">この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="8e287-211">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-214">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;" Usage="iJobOperations.ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync (jobId, jobListPreparationAndReleaseTaskStatusOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-215">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-215">The ID of the job.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            <span data-ttu-id="8e287-216">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-216">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-217">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-217">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-219">ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8e287-219">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-220">この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。</span><span class="sxs-lookup"><span data-stu-id="8e287-220">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="8e287-221">これには、プールからからは削除されているノードが含まれます。</span><span class="sxs-lookup"><span data-stu-id="8e287-221">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="8e287-222">この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="8e287-222">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-223">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-223">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-224">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-224">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-225">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-225">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" Usage="iJobOperations.ListWithHttpMessagesAsync (jobListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobListOptions">
            <span data-ttu-id="8e287-226">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-226">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-227">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-227">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-228">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-229">指定されたアカウント内のジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8e287-229">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-230">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-230">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e287-231">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-231">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-232">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-232">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PatchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt;" Usage="iJobOperations.PatchWithHttpMessagesAsync (jobId, jobPatchParameter, jobPatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-233">プロパティを更新するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-233">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobPatchParameter">
            <span data-ttu-id="8e287-234">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8e287-234">The parameters for the request.</span></span>
            </param>
        <param name="jobPatchOptions">
            <span data-ttu-id="8e287-235">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-235">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-236">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-236">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-238">指定したジョブのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e287-238">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-239">これには、要求で指定されたジョブのプロパティのみが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8e287-239">This replaces only the job properties specified in the request.</span></span> <span data-ttu-id="8e287-240">たとえば、ジョブの制約には、要求が制約要素を指定しない場合は、既存の制約維持ジョブにします。</span><span class="sxs-lookup"><span data-stu-id="8e287-240">For example, if the job has constraints, and a request does not specify the constraints element, then the job keeps the existing constraints.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-241">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-241">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-242">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-242">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.TerminateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt;" Usage="iJobOperations.TerminateWithHttpMessagesAsync (jobId, terminateReason, jobTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-243">終了するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-243">The ID of the job to terminate.</span></span>
            </param>
        <param name="terminateReason">
            <span data-ttu-id="8e287-244">ジョブの TerminateReason として表示するテキストです。</span><span class="sxs-lookup"><span data-stu-id="8e287-244">The text you want to appear as the job's TerminateReason.</span></span> <span data-ttu-id="8e287-245">既定値は、'UserTerminate' です。</span><span class="sxs-lookup"><span data-stu-id="8e287-245">The default is 'UserTerminate'.</span></span>
            </param>
        <param name="jobTerminateOptions">
            <span data-ttu-id="8e287-246">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-246">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-247">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-247">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-248">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-248">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-249">完了としてマークして、指定されたジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="8e287-249">Terminates the specified job, marking it as completed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-250">ジョブの終了要求を受信すると、Batch service はジョブを最終状態に設定します。</span><span class="sxs-lookup"><span data-stu-id="8e287-250">When a Terminate Job request is received, the Batch service sets the job to the terminating state.</span></span> <span data-ttu-id="8e287-251">バッチ サービスは、ジョブに関連付けられているアクティブなまたは実行中のタスクを終了し、必要なジョブのリリース タスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="8e287-251">The Batch service then terminates any active or running tasks associated with the job, and runs any required Job Release tasks.</span></span> <span data-ttu-id="8e287-252">ジョブは、完了した状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="8e287-252">The job then moves into the completed state.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-253">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-253">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-254">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-254">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.UpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt;" Usage="iJobOperations.UpdateWithHttpMessagesAsync (jobId, jobUpdateParameter, jobUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="8e287-255">プロパティを更新するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="8e287-255">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobUpdateParameter">
            <span data-ttu-id="8e287-256">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8e287-256">The parameters for the request.</span></span>
            </param>
        <param name="jobUpdateOptions">
            <span data-ttu-id="8e287-257">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8e287-257">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e287-258">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e287-258">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e287-259">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e287-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e287-260">指定したジョブのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e287-260">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e287-261">これにより、ジョブのすべての更新可能なプロパティが完全に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8e287-261">This fully replaces all the updateable properties of the job.</span></span> <span data-ttu-id="8e287-262">たとえば、ジョブに関連付けられている制約が設定されている場合、この要求に制約が指定されていない場合、Batch service、既存の制約は削除します。</span><span class="sxs-lookup"><span data-stu-id="8e287-262">For example, if the job has constraints associated with it and if constraints is not specified with this request, then the Batch service will remove the existing constraints.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="8e287-263">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-263">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e287-264">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e287-264">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>