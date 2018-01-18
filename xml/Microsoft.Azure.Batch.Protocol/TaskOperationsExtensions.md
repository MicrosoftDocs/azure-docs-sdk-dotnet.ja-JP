<Type Name="TaskOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TaskOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TaskOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TaskOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TaskOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b7fd-101">TaskOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-101">Extension methods for TaskOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add (operations, jobId, task, taskAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-103">タスクを追加するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-103">The ID of the job to which the task is to be added.</span></span>
            </param>
        <param name="task">
            <span data-ttu-id="1b7fd-104">追加するタスク。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-104">The task to be added.</span></span>
            </param>
        <param name="taskAddOptions">
            <span data-ttu-id="1b7fd-105">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-105">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-106">指定されたジョブにタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-106">Adds a task to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-107">追加からタスクを完了するまでの最長有効期間は、7 日間です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-107">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="1b7fd-108">バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-108">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync (operations, jobId, task, taskAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-109">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-110">タスクを追加するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-110">The ID of the job to which the task is to be added.</span></span>
            </param>
        <param name="task">
            <span data-ttu-id="1b7fd-111">追加するタスク。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-111">The task to be added.</span></span>
            </param>
        <param name="taskAddOptions">
            <span data-ttu-id="1b7fd-112">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-112">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-114">指定されたジョブにタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-114">Adds a task to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-115">追加からタスクを完了するまでの最長有効期間は、7 日間です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-115">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="1b7fd-116">バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-116">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions)" />
      <MemberSignature Language="F#" Value="static member AddCollection : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection (operations, jobId, value, taskAddCollectionOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-117">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-118">タスクのコレクションを追加するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-118">The ID of the job to which the task collection is to be added.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="1b7fd-119">追加するタスクのコレクション。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-119">The collection of tasks to add.</span></span> <span data-ttu-id="1b7fd-120">このコレクションのシリアル化された合計サイズは 4 MB 未満である必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-120">The total serialized size of this collection must be less than 4MB.</span></span> <span data-ttu-id="1b7fd-121">(たとえば、各タスクは 100 のリソース ファイルや環境変数の場合など)、4 MB を超える場合は、要求はコード 'RequestBodyTooLarge' で失敗し、タスクが削減再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-121">If it is greater than 4MB (for example if each task has 100's of resource files or environment variables), the request will fail with code 'RequestBodyTooLarge' and should be retried again with fewer tasks.</span></span>
            </param>
        <param name="taskAddCollectionOptions">
            <span data-ttu-id="1b7fd-122">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-122">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-123">指定されたジョブにタスクのコレクションを追加します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-123">Adds a collection of tasks to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-124">各タスクが必要となる一意の ID に注意してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-124">Note that each task must have a unique ID.</span></span> <span data-ttu-id="1b7fd-125">バッチ サービスは、タスクがこの要求で送信された順序と同じ順序で各タスクの結果を返さない場合があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-125">The Batch service may not return the results for each task in the same order the tasks were submitted in this request.</span></span> <span data-ttu-id="1b7fd-126">場合は、サーバーがタイムアウトするか、要求時に、接続が閉じられる、要求あった可能性があります部分的または完全に処理された、またはまったくです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-126">If the server times out or the connection is closed during the request, the request may have been partially or fully processed, or not at all.</span></span> <span data-ttu-id="1b7fd-127">このような場合、ユーザーは再要求を発行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-127">In such cases, the user should re-issue the request.</span></span> <span data-ttu-id="1b7fd-128">再要求を発行する際に、エラーを正しく処理するには、ユーザーの責任であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-128">Note that it is up to the user to correctly handle failures when re-issuing a request.</span></span>
            <span data-ttu-id="1b7fd-129">たとえば、前の操作が成功した場合、再試行は作成されません余分なタスクが予期せずように再試行中に同じタスク Id を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-129">For example, you should use the same task IDs during a retry so that if the prior operation succeeded, the retry will not create extra tasks unexpectedly.</span></span> <span data-ttu-id="1b7fd-130">応答の追加に失敗したすべてのタスクが含まれている場合、クライアントは要求を再試行できます。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-130">If the response contains any tasks which failed to add, a client can retry the request.</span></span> <span data-ttu-id="1b7fd-131">再試行を追加し、最初の試行で正常に追加されたタスクを省略する場合に失敗したタスクのみを再送信する最も効率的です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-131">In a retry, it is most efficient to resubmit only tasks that failed to add, and to omit tasks that were successfully added on the first attempt.</span></span> <span data-ttu-id="1b7fd-132">追加からタスクを完了するまでの最長有効期間は、7 日間です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-132">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="1b7fd-133">バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-133">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddCollectionAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync (operations, jobId, value, taskAddCollectionOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddCollectionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-134">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-135">タスクのコレクションを追加するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-135">The ID of the job to which the task collection is to be added.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="1b7fd-136">追加するタスクのコレクション。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-136">The collection of tasks to add.</span></span> <span data-ttu-id="1b7fd-137">このコレクションのシリアル化された合計サイズは 4 MB 未満である必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-137">The total serialized size of this collection must be less than 4MB.</span></span> <span data-ttu-id="1b7fd-138">(たとえば、各タスクは 100 のリソース ファイルや環境変数の場合など)、4 MB を超える場合は、要求はコード 'RequestBodyTooLarge' で失敗し、タスクが削減再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-138">If it is greater than 4MB (for example if each task has 100's of resource files or environment variables), the request will fail with code 'RequestBodyTooLarge' and should be retried again with fewer tasks.</span></span>
            </param>
        <param name="taskAddCollectionOptions">
            <span data-ttu-id="1b7fd-139">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-139">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-141">指定されたジョブにタスクのコレクションを追加します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-141">Adds a collection of tasks to the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-142">各タスクが必要となる一意の ID に注意してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-142">Note that each task must have a unique ID.</span></span> <span data-ttu-id="1b7fd-143">バッチ サービスは、タスクがこの要求で送信された順序と同じ順序で各タスクの結果を返さない場合があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-143">The Batch service may not return the results for each task in the same order the tasks were submitted in this request.</span></span> <span data-ttu-id="1b7fd-144">場合は、サーバーがタイムアウトするか、要求時に、接続が閉じられる、要求あった可能性があります部分的または完全に処理された、またはまったくです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-144">If the server times out or the connection is closed during the request, the request may have been partially or fully processed, or not at all.</span></span> <span data-ttu-id="1b7fd-145">このような場合、ユーザーは再要求を発行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-145">In such cases, the user should re-issue the request.</span></span> <span data-ttu-id="1b7fd-146">再要求を発行する際に、エラーを正しく処理するには、ユーザーの責任であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-146">Note that it is up to the user to correctly handle failures when re-issuing a request.</span></span>
            <span data-ttu-id="1b7fd-147">たとえば、前の操作が成功した場合、再試行は作成されません余分なタスクが予期せずように再試行中に同じタスク Id を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-147">For example, you should use the same task IDs during a retry so that if the prior operation succeeded, the retry will not create extra tasks unexpectedly.</span></span> <span data-ttu-id="1b7fd-148">応答の追加に失敗したすべてのタスクが含まれている場合、クライアントは要求を再試行できます。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-148">If the response contains any tasks which failed to add, a client can retry the request.</span></span> <span data-ttu-id="1b7fd-149">再試行を追加し、最初の試行で正常に追加されたタスクを省略する場合に失敗したタスクのみを再送信する最も効率的です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-149">In a retry, it is most efficient to resubmit only tasks that failed to add, and to omit tasks that were successfully added on the first attempt.</span></span> <span data-ttu-id="1b7fd-150">追加からタスクを完了するまでの最長有効期間は、7 日間です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-150">The maximum lifetime of a task from addition to completion is 7 days.</span></span> <span data-ttu-id="1b7fd-151">バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-151">If a task has not completed within 7 days of being added it will be terminated by the Batch service and left in whatever state it was in at that time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete (operations, jobId, taskId, taskDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-152">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-153">タスクを削除するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-153">The ID of the job from which to delete the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-154">削除するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-154">The ID of the task to delete.</span></span>
            </param>
        <param name="taskDeleteOptions">
            <span data-ttu-id="1b7fd-155">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-155">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-156">指定されたジョブからタスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-156">Deletes a task from the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-157">タスクを削除すると、すべての行く先コンピューティング ノード上のディレクトリにファイルの (時刻に関係なく、保有期間) も削除されます。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-157">When a task is deleted, all of the files in its directory on the compute node where it ran are also deleted (regardless of the retention time).</span></span> <span data-ttu-id="1b7fd-158">マルチ インスタンスのタスクの削除タスクの操作に適用されます同期的に主要なタスクです。サブタスクとそのファイルに非同期的に、バック グラウンドでは削除し、されます。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-158">For multi-instance tasks, the delete task operation applies synchronously to the primary task; subtasks and their files are then deleted asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync (operations, jobId, taskId, taskDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-159">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-160">タスクを削除するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-160">The ID of the job from which to delete the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-161">削除するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-161">The ID of the task to delete.</span></span>
            </param>
        <param name="taskDeleteOptions">
            <span data-ttu-id="1b7fd-162">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-162">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-164">指定されたジョブからタスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-164">Deletes a task from the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-165">タスクを削除すると、すべての行く先コンピューティング ノード上のディレクトリにファイルの (時刻に関係なく、保有期間) も削除されます。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-165">When a task is deleted, all of the files in its directory on the compute node where it ran are also deleted (regardless of the retention time).</span></span> <span data-ttu-id="1b7fd-166">マルチ インスタンスのタスクの削除タスクの操作に適用されます同期的に主要なタスクです。サブタスクとそのファイルに非同期的に、バック グラウンドでは削除し、されます。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-166">For multi-instance tasks, the delete task operation applies synchronously to the primary task; subtasks and their files are then deleted asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTask Get (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTask Get(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTask" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get (operations, jobId, taskId, taskGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-167">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-168">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-168">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-169">情報を取得するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-169">The ID of the task to get information about.</span></span>
            </param>
        <param name="taskGetOptions">
            <span data-ttu-id="1b7fd-170">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-170">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-171">指定されたタスクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-171">Gets information about the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-172">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-172">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="1b7fd-173">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-173">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync (operations, jobId, taskId, taskGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-174">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-175">タスクが含まれているジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-175">The ID of the job that contains the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-176">情報を取得するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-176">The ID of the task to get information about.</span></span>
            </param>
        <param name="taskGetOptions">
            <span data-ttu-id="1b7fd-177">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-177">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-179">指定されたタスクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-179">Gets information about the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-180">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-180">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="1b7fd-181">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-181">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List (operations, jobId, taskListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-182">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-183">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-183">The ID of the job.</span></span>
            </param>
        <param name="taskListOptions">
            <span data-ttu-id="1b7fd-184">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-184">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-185">すべての指定されたジョブに関連付けられているタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-185">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-186">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-186">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="1b7fd-187">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-187">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync (operations, jobId, taskListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-188">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-189">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-189">The ID of the job.</span></span>
            </param>
        <param name="taskListOptions">
            <span data-ttu-id="1b7fd-190">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-190">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-192">すべての指定されたジョブに関連付けられているタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-192">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-193">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-193">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="1b7fd-194">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-194">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext (operations, nextPageLink, taskListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b7fd-196">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="taskListNextOptions">
            <span data-ttu-id="1b7fd-197">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-197">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-198">すべての指定されたジョブに関連付けられているタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-198">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-199">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-199">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="1b7fd-200">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-200">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync (operations, nextPageLink, taskListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-201">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1b7fd-202">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="taskListNextOptions">
            <span data-ttu-id="1b7fd-203">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-203">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-204">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-205">すべての指定されたジョブに関連付けられているタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-205">Lists all of the tasks that are associated with the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-206">複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-206">For multi-instance tasks, information such as affinityId, executionInfo and nodeInfo refer to the primary task.</span></span> <span data-ttu-id="1b7fd-207">一覧のサブタスク API を使用して、サブタスクについての情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-207">Use the list subtasks API to retrieve information about subtasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions)" />
      <MemberSignature Language="F#" Value="static member ListSubtasks : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks (operations, jobId, taskId, taskListSubtasksOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-208">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-209">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-209">The ID of the job.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-210">タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-210">The ID of the task.</span></span>
            </param>
        <param name="taskListSubtasksOptions">
            <span data-ttu-id="1b7fd-211">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-211">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-212">すべての複数インスタンスの指定したタスクに関連付けられているサブタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-212">Lists all of the subtasks that are associated with the specified multi-instance task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-213">タスクがタスクを複数のインスタンスではない場合この空のコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-213">If the task is not a multi-instance task then this returns an empty collection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSubtasksAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync (operations, jobId, taskId, taskListSubtasksOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListSubtasksAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-214">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-215">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-215">The ID of the job.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-216">タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-216">The ID of the task.</span></span>
            </param>
        <param name="taskListSubtasksOptions">
            <span data-ttu-id="1b7fd-217">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-217">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-219">すべての複数インスタンスの指定したタスクに関連付けられているサブタスクの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-219">Lists all of the subtasks that are associated with the specified multi-instance task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-220">タスクがタスクを複数のインスタンスではない場合この空のコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-220">If the task is not a multi-instance task then this returns an empty collection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reactivate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions)" />
      <MemberSignature Language="F#" Value="static member Reactivate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate (operations, jobId, taskId, taskReactivateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-221">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-222">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-222">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-223">再アクティブ化するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-223">The ID of the task to reactivate.</span></span>
            </param>
        <param name="taskReactivateOptions">
            <span data-ttu-id="1b7fd-224">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-224">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-225">許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-225">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-226">再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-226">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span> <span data-ttu-id="1b7fd-227">タスクの状態はアクティブに変更します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-227">The task's state is changed to active.</span></span> <span data-ttu-id="1b7fd-228">タスクが完了した状態である不要になった、以前の終了コードまたはエラー情報は再アクティブ化の後に使用できなくします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-228">As the task is no longer in the completed state, any previous exit code or failure information is no longer available after reactivation.</span></span> <span data-ttu-id="1b7fd-229">タスクの再アクティブ化するたびに、再試行カウントが 0 にリセットします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-229">Each time a task is reactivated, its retry count is reset to 0.</span></span> <span data-ttu-id="1b7fd-230">完了していない、または正常に (終了コード 0) の以前に完了したタスクを再アクティブ化は失敗します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-230">Reactivation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span> <span data-ttu-id="1b7fd-231">さらに、ジョブが完了しました (が終了または削除する) 場合は失敗します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-231">Additionally, it will fail if the job has completed (or is terminating or deleting).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReactivateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync (operations, jobId, taskId, taskReactivateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ReactivateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-232">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-232">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-233">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-233">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-234">再アクティブ化するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-234">The ID of the task to reactivate.</span></span>
            </param>
        <param name="taskReactivateOptions">
            <span data-ttu-id="1b7fd-235">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-235">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-237">許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-237">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-238">再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-238">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span> <span data-ttu-id="1b7fd-239">タスクの状態はアクティブに変更します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-239">The task's state is changed to active.</span></span> <span data-ttu-id="1b7fd-240">タスクが完了した状態である不要になった、以前の終了コードまたはエラー情報は再アクティブ化の後に使用できなくします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-240">As the task is no longer in the completed state, any previous exit code or failure information is no longer available after reactivation.</span></span> <span data-ttu-id="1b7fd-241">タスクの再アクティブ化するたびに、再試行カウントが 0 にリセットします。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-241">Each time a task is reactivated, its retry count is reset to 0.</span></span> <span data-ttu-id="1b7fd-242">完了していない、または正常に (終了コード 0) の以前に完了したタスクを再アクティブ化は失敗します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-242">Reactivation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span> <span data-ttu-id="1b7fd-243">さらに、ジョブが完了しました (が終了または削除する) 場合は失敗します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-243">Additionally, it will fail if the job has completed (or is terminating or deleting).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate (operations, jobId, taskId, taskTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-244">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-244">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-245">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-245">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-246">タスクが終了するの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-246">The ID of the task to terminate.</span></span>
            </param>
        <param name="taskTerminateOptions">
            <span data-ttu-id="1b7fd-247">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-247">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-248">指定したタスクを終了します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-248">Terminates the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-249">タスクが終了したとき、完了状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-249">When the task has been terminated, it moves to the completed state.</span></span> <span data-ttu-id="1b7fd-250">マルチ インスタンスのタスクの終了タスク操作に適用されます同期的に主要なタスクです。サブタスクは、バック グラウンドで非同期的に終了します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-250">For multi-instance tasks, the terminate task operation applies synchronously to the primary task; subtasks are then terminated asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync (operations, jobId, taskId, taskTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-251">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-252">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-252">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-253">タスクが終了するの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-253">The ID of the task to terminate.</span></span>
            </param>
        <param name="taskTerminateOptions">
            <span data-ttu-id="1b7fd-254">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-254">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-256">指定したタスクを終了します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-256">Terminates the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b7fd-257">タスクが終了したとき、完了状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-257">When the task has been terminated, it moves to the completed state.</span></span> <span data-ttu-id="1b7fd-258">マルチ インスタンスのタスクの終了タスク操作に適用されます同期的に主要なタスクです。サブタスクは、バック グラウンドで非同期的に終了します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-258">For multi-instance tasks, the terminate task operation applies synchronously to the primary task; subtasks are then terminated asynchronously in the background.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update (operations, jobId, taskId, constraints, taskUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-259">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-259">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-260">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-260">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-261">更新するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-261">The ID of the task to update.</span></span>
            </param>
        <param name="constraints">
            <span data-ttu-id="1b7fd-262">このタスクに適用される制約します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-262">Constraints that apply to this task.</span></span> <span data-ttu-id="1b7fd-263">省略した場合、タスクは、既定の制約を付与します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-263">If omitted, the task is given the default constraints.</span></span> <span data-ttu-id="1b7fd-264">複数インスタンスの作業、リテンション期間を更新、主要なタスクにのみ適用されますおよびサブタスクがありません。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-264">For multi-instance tasks, updating the retention time applies only to the primary task and not subtasks.</span></span>
            </param>
        <param name="taskUpdateOptions">
            <span data-ttu-id="1b7fd-265">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-265">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-266">指定したタスクのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-266">Updates the properties of the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync (operations, jobId, taskId, constraints, taskUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1b7fd-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-267">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="1b7fd-268">タスクを含むジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-268">The ID of the job containing the task.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="1b7fd-269">更新するタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-269">The ID of the task to update.</span></span>
            </param>
        <param name="constraints">
            <span data-ttu-id="1b7fd-270">このタスクに適用される制約します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-270">Constraints that apply to this task.</span></span> <span data-ttu-id="1b7fd-271">省略した場合、タスクは、既定の制約を付与します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-271">If omitted, the task is given the default constraints.</span></span> <span data-ttu-id="1b7fd-272">複数インスタンスの作業、リテンション期間を更新、主要なタスクにのみ適用されますおよびサブタスクがありません。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-272">For multi-instance tasks, updating the retention time applies only to the primary task and not subtasks.</span></span>
            </param>
        <param name="taskUpdateOptions">
            <span data-ttu-id="1b7fd-273">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="1b7fd-273">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b7fd-274">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-274">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b7fd-275">指定したタスクのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="1b7fd-275">Updates the properties of the specified task.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>