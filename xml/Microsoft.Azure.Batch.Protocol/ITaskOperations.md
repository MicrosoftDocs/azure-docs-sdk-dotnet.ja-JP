<Type Name="ITaskOperations" FullName="Microsoft.Azure.Batch.Protocol.ITaskOperations">
  <TypeSignature Language="C#" Value="public interface ITaskOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITaskOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ITaskOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITaskOperations" />
  <TypeSignature Language="F#" Value="type ITaskOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f79e4-101">TaskOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="f79e4-101">TaskOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddCollectionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync (string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync(string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddCollectionWithHttpMessagesAsync(System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddCollectionWithHttpMessagesAsync : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;" Usage="iTaskOperations.AddCollectionWithHttpMessagesAsync (jobId, value, taskAddCollectionOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-102">タスクのコレクションを追加するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-102">The ID of the job to which the task collection is to be added.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="f79e4-103">追加するタスクのコレクション。</span><span class="sxs-lookup"><span data-stu-id="f79e4-103">The collection of tasks to add.</span></span> <span data-ttu-id="f79e4-104">このコレクションのシリアル化された合計サイズは 4 MB 未満である必要があります。</span><span class="sxs-lookup"><span data-stu-id="f79e4-104">The total serialized size of this collection must be less than 4MB.</span></span> <span data-ttu-id="f79e4-105">(たとえば、各タスクは 100 のリソース ファイルや環境変数の場合など)、4 MB を超える場合は、要求はコード 'RequestBodyTooLarge' で失敗し、タスクが削減再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f79e4-105">If it is greater than 4MB (for example if each task has 100's of resource files or environment variables), the request will fail with code 'RequestBodyTooLarge' and should be retried again with fewer tasks.</span></span>
            </param>
        <param name="taskAddCollectionOptions">
            <span data-ttu-id="f79e4-106">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-106">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-109">指定されたジョブにタスクのコレクションを追加します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-109">Adds a collection of tasks to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-110">各タスクが必要となる一意の ID に注意してください。</span><span class="sxs-lookup"><span data-stu-id="f79e4-110">Note that each task must have a unique ID.</span></span> <span data-ttu-id="f79e4-111">バッチ サービスは、タスクがこの要求で送信された順序と同じ順序で各タスクの結果を返さない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f79e4-111">The Batch service may not return the results for each task in the same order the tasks were submitted in this request.</span></span> <span data-ttu-id="f79e4-112">場合は、サーバーがタイムアウトするか、要求時に、接続が閉じられる、要求あった可能性があります部分的または完全に処理された、またはまったくです。</span><span class="sxs-lookup"><span data-stu-id="f79e4-112">If the server times out or the connection is closed during the request, the request may have been partially or fully processed, or not at all.</span></span> <span data-ttu-id="f79e4-113">このような場合、ユーザーは再要求を発行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f79e4-113">In such cases, the user should re-issue the request.</span></span> <span data-ttu-id="f79e4-114">再要求を発行する際に、エラーを正しく処理するには、ユーザーの責任であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f79e4-114">Note that it is up to the user to correctly handle failures when re-issuing a request.</span></span> <span data-ttu-id="f79e4-115">たとえば、前の操作が成功した場合、再試行は作成されません余分なタスクが予期せずように再試行中に同じタスク Id を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f79e4-115">For example, you should use the same task IDs during a retry so that if the prior operation succeeded, the retry will not create extra tasks unexpectedly.</span></span> <span data-ttu-id="f79e4-116">応答の追加に失敗したすべてのタスクが含まれている場合、クライアントは要求を再試行できます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-116">If the response contains any tasks which failed to add, a client can retry the request.</span></span> <span data-ttu-id="f79e4-117">再試行を追加し、最初の試行で正常に追加されたタスクを省略する場合に失敗したタスクのみを再送信する最も効率的です。</span><span class="sxs-lookup"><span data-stu-id="f79e4-117">In a retry, it is most efficient to resubmit only tasks that failed to add, and to omit tasks that were successfully added on the first attempt.</span></span> <span data-ttu-id="f79e4-118">追加からタスクを完了するまでの最長有効期間は、7 日間です。</span><span class="sxs-lookup"><span data-stu-id="f79e4-118">The maximum lifetime of a task from addition to completion is 7 days.</span></span>
            <span data-ttu-id="f79e4-119">バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。</span><span class="sxs-lookup"><span data-stu-id="f79e4-119">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f79e4-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;" Usage="iTaskOperations.AddWithHttpMessagesAsync (jobId, task, taskAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-123">タスクを追加するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-123">The ID of the job to which the task is to be added.</span></span>
            </param>
        <param name="task">
            <span data-ttu-id="f79e4-124">追加するタスク。</span><span class="sxs-lookup"><span data-stu-id="f79e4-124">The task to be added.</span></span>
            </param>
        <param name="taskAddOptions">
            <span data-ttu-id="f79e4-125">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-125">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-128">指定されたジョブにタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-128">Adds a task to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-129">追加からタスクを完了するまでの最長有効期間は、7 日間です。</span><span class="sxs-lookup"><span data-stu-id="f79e4-129">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="f79e4-130">バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。</span><span class="sxs-lookup"><span data-stu-id="f79e4-130">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.DeleteWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;" Usage="iTaskOperations.DeleteWithHttpMessagesAsync (jobId, taskId, taskDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-133">タスクを削除するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-133">The ID of the job from which to delete the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="f79e4-134">削除するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-134">The ID of the task to delete.</span></span>
            </param>
        <param name="taskDeleteOptions">
            <span data-ttu-id="f79e4-135">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-135">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-138">指定されたジョブからタスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-138">Deletes a task from the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-139">タスクを削除すると、すべての行く先コンピューティング ノード上のディレクトリにファイルの (時刻に関係なく、保有期間) も削除されます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-139">When a task is deleted, all of the files in its directory on the compute node where it ran are also deleted (regardless of the retention time).</span></span> <span data-ttu-id="f79e4-140">マルチ インスタンスのタスクの削除タスクの操作に適用されます同期的に主要なタスクです。サブタスクとそのファイルに非同期的に、バック グラウンドでは削除し、されます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-140">For multi-instance tasks, the delete task operation applies synchronously to the primary task; subtasks and their files are then deleted asynchronously in the background.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask, class Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask, Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;" Usage="iTaskOperations.GetWithHttpMessagesAsync (jobId, taskId, taskGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-143">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-143">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="f79e4-144">情報を取得するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-144">The ID of the task to get information about.</span></span>
            </param>
        <param name="taskGetOptions">
            <span data-ttu-id="f79e4-145">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-145">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-148">指定されたタスクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-148">Gets information about the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-149">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="f79e4-149">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="f79e4-150">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-150">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f79e4-152">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListNextWithHttpMessagesAsync (nextPageLink, taskListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f79e4-154">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f79e4-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="taskListNextOptions">
            <span data-ttu-id="f79e4-155">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-155">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-158">すべての指定されたジョブに関連付けられているタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-158">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-159">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="f79e4-159">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="f79e4-160">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-160">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-161">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f79e4-162">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-162">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListSubtasksWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSubtasksWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;" Usage="iTaskOperations.ListSubtasksWithHttpMessagesAsync (jobId, taskId, taskListSubtasksOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-164">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-164">The ID of the job.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="f79e4-165">タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-165">The ID of the task.</span></span>
            </param>
        <param name="taskListSubtasksOptions">
            <span data-ttu-id="f79e4-166">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-166">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-169">すべての複数インスタンスの指定したタスクに関連付けられているサブタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-169">Lists all of the subtasks that are associated with the specified multi-instance task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-170">タスクがタスクを複数のインスタンスではない場合この空のコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-170">If the task is not a multi-instance task then this returns an empty collection.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-171">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f79e4-172">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-172">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-173">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListWithHttpMessagesAsync (jobId, taskListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-174">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-174">The ID of the job.</span></span>
            </param>
        <param name="taskListOptions">
            <span data-ttu-id="f79e4-175">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-175">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-178">すべての指定されたジョブに関連付けられているタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-178">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-179">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="f79e4-179">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="f79e4-180">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-180">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-181">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f79e4-182">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-183">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReactivateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ReactivateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReactivateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;" Usage="iTaskOperations.ReactivateWithHttpMessagesAsync (jobId, taskId, taskReactivateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-184">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-184">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="f79e4-185">再アクティブ化するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-185">The ID of the task to reactivate.</span></span>
            </param>
        <param name="taskReactivateOptions">
            <span data-ttu-id="f79e4-186">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-186">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-189">許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-189">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-190">再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。</span><span class="sxs-lookup"><span data-stu-id="f79e4-190">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span> <span data-ttu-id="f79e4-191">タスクの状態はアクティブに変更します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-191">The task's state is changed to active.</span></span> <span data-ttu-id="f79e4-192">タスクが完了した状態である不要になった、以前の終了コードまたはエラー情報は再アクティブ化の後に使用できなくします。</span><span class="sxs-lookup"><span data-stu-id="f79e4-192">As the task is no longer in the completed state, any previous exit code or failure information is no longer available after reactivation.</span></span> <span data-ttu-id="f79e4-193">タスクの再アクティブ化するたびに、再試行カウントが 0 にリセットします。</span><span class="sxs-lookup"><span data-stu-id="f79e4-193">Each time a task is reactivated, its retry count is reset to 0.</span></span>
            <span data-ttu-id="f79e4-194">完了していない、または正常に (終了コード 0) の以前に完了したタスクを再アクティブ化は失敗します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-194">Reactivation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span>
            <span data-ttu-id="f79e4-195">さらに、ジョブが完了しました (が終了または削除する) 場合は失敗します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-195">Additionally, it will fail if the job has completed (or is terminating or deleting).</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-197">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-197">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.TerminateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;" Usage="iTaskOperations.TerminateWithHttpMessagesAsync (jobId, taskId, taskTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-198">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-198">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="f79e4-199">タスクが終了するの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-199">The ID of the task to terminate.</span></span>
            </param>
        <param name="taskTerminateOptions">
            <span data-ttu-id="f79e4-200">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-200">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-201">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-203">指定したタスクを終了します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-203">Terminates the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f79e4-204">タスクが終了したとき、完了状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-204">When the task has been terminated, it moves to the completed state.</span></span>
            <span data-ttu-id="f79e4-205">マルチ インスタンスのタスクの終了タスク操作に適用されます同期的に主要なタスクです。サブタスクは、バック グラウンドで非同期的に終了します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-205">For multi-instance tasks, the terminate task operation applies synchronously to the primary task; subtasks are then terminated asynchronously in the background.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-206">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-206">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;" Usage="iTaskOperations.UpdateWithHttpMessagesAsync (jobId, taskId, constraints, taskUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            <span data-ttu-id="f79e4-208">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-208">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="f79e4-209">更新するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="f79e4-209">The ID of the task to update.</span></span>
            </param>
        <param name="constraints">
            <span data-ttu-id="f79e4-210">このタスクに適用される制約します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-210">Constraints that apply to this task.</span></span> <span data-ttu-id="f79e4-211">省略した場合、タスクは、既定の制約を付与します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-211">If omitted, the task is given the default constraints.</span></span> <span data-ttu-id="f79e4-212">複数インスタンスの作業、リテンション期間を更新、主要なタスクにのみ適用されますおよびサブタスクがありません。</span><span class="sxs-lookup"><span data-stu-id="f79e4-212">For multi-instance tasks, updating the retention time applies only to the primary task and not subtasks.</span></span>
            </param>
        <param name="taskUpdateOptions">
            <span data-ttu-id="f79e4-213">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f79e4-213">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f79e4-214">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-214">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f79e4-215">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f79e4-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f79e4-216">指定したタスクのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="f79e4-216">Updates the properties of the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            <span data-ttu-id="f79e4-217">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-217">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f79e4-218">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f79e4-218">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>