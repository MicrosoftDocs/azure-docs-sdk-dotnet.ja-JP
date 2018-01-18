<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
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
            <span data-ttu-id="7dbaf-101">JobOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-101">Extension methods for JobOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders Add (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders Add(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Add (operations, job, jobAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-102">The operations group for this extension method.</span></span>
            </param>
        <param name="job">
            <span data-ttu-id="7dbaf-103">追加するジョブです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-103">The job to be added.</span></span>
            </param>
        <param name="jobAddOptions">
            <span data-ttu-id="7dbaf-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-105">指定されたアカウントに、ジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-105">Adds a job to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-106">バッチ サービスでは、ジョブの一部として行われる処理を制御する 2 つの方法をサポートします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-106">The Batch service supports two ways to control the work done as part of a job.</span></span> <span data-ttu-id="7dbaf-107">最初の方法では、ユーザーは、ジョブ マネージャー タスクを指定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-107">In the first approach, the user specifies a Job Manager task.</span></span> <span data-ttu-id="7dbaf-108">バッチ サービスは、ジョブを開始する準備ができたときに、このタスクを起動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-108">The Batch service launches this task when it is ready to start the job.</span></span> <span data-ttu-id="7dbaf-109">ジョブ マネージャー タスクは、タスクの Api を使用して、このジョブで実行される他のすべてのタスクを制御します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-109">The Job Manager task controls all other tasks that run under this job, by using the Task APIs.</span></span> <span data-ttu-id="7dbaf-110">2 番目の方法で、ユーザーは直接タスク Api を使用してアクティブなジョブのタスクの実行を制御します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-110">In the second approach, the user directly controls the execution of tasks under an active job, by using the Task APIs.</span></span> <span data-ttu-id="7dbaf-111">注意してください。 ジョブの名前を付けるときは、ユーザー名またはシークレット プロジェクト名などの機密情報が含まれないようにします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-111">Also note: when naming jobs, avoid including sensitive information such as user names or secret project names.</span></span> <span data-ttu-id="7dbaf-112">この情報は、Microsoft サポート エンジニアにアクセスできる製品利用統計情報ログに表示可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-112">This information may appear in telemetry logs accessible to Microsoft Support engineers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.AddAsync (operations, job, jobAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;AddAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-113">The operations group for this extension method.</span></span>
            </param>
        <param name="job">
            <span data-ttu-id="7dbaf-114">追加するジョブです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-114">The job to be added.</span></span>
            </param>
        <param name="jobAddOptions">
            <span data-ttu-id="7dbaf-115">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-115">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-117">指定されたアカウントに、ジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-117">Adds a job to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-118">バッチ サービスでは、ジョブの一部として行われる処理を制御する 2 つの方法をサポートします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-118">The Batch service supports two ways to control the work done as part of a job.</span></span> <span data-ttu-id="7dbaf-119">最初の方法では、ユーザーは、ジョブ マネージャー タスクを指定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-119">In the first approach, the user specifies a Job Manager task.</span></span> <span data-ttu-id="7dbaf-120">バッチ サービスは、ジョブを開始する準備ができたときに、このタスクを起動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-120">The Batch service launches this task when it is ready to start the job.</span></span> <span data-ttu-id="7dbaf-121">ジョブ マネージャー タスクは、タスクの Api を使用して、このジョブで実行される他のすべてのタスクを制御します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-121">The Job Manager task controls all other tasks that run under this job, by using the Task APIs.</span></span> <span data-ttu-id="7dbaf-122">2 番目の方法で、ユーザーは直接タスク Api を使用してアクティブなジョブのタスクの実行を制御します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-122">In the second approach, the user directly controls the execution of tasks under an active job, by using the Task APIs.</span></span> <span data-ttu-id="7dbaf-123">注意してください。 ジョブの名前を付けるときは、ユーザー名またはシークレット プロジェクト名などの機密情報が含まれないようにします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-123">Also note: when naming jobs, avoid including sensitive information such as user names or secret project names.</span></span> <span data-ttu-id="7dbaf-124">この情報は、Microsoft サポート エンジニアにアクセスできる製品利用統計情報ログに表示可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-124">This information may appear in telemetry logs accessible to Microsoft Support engineers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Delete (operations, jobId, jobDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-125">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-126">削除するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-126">The ID of the job to delete.</span></span>
            </param>
        <param name="jobDeleteOptions">
            <span data-ttu-id="7dbaf-127">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-127">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-128">ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-128">Deletes a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-129">ジョブを削除すると、そのジョブの一部であるすべてのタスクとすべてのジョブの統計も削除されます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-129">Deleting a job also deletes all tasks that are part of that job, and all job statistics.</span></span> <span data-ttu-id="7dbaf-130">タスクのデータの保有期間も上書きされます。つまり、ジョブにコンピューティング ノードで保持されているタスクが含まれている場合、バッチ サービスをそれらのタスクの作業ディレクトリとそのすべてのコンテンツを削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-130">This also overrides the retention period for task data; that is, if the job contains tasks which are still retained on compute nodes, the Batch services deletes those tasks' working directories and all their contents.</span></span>  <span data-ttu-id="7dbaf-131">ジョブの削除要求を受信すると、バッチ サービスは、削除の状態にジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-131">When a Delete Job request is received, the Batch service sets the job to the deleting state.</span></span> <span data-ttu-id="7dbaf-132">ジョブの状態を削除するのには上のすべての更新操作は、追加情報をジョブが削除されていることを示すステータス コード 409 (Conflict) で失敗します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-132">All update operations on a job that is in deleting state will fail with status code 409 (Conflict), with additional information indicating that the job is being deleted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DeleteAsync (operations, jobId, jobDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-133">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-134">削除するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-134">The ID of the job to delete.</span></span>
            </param>
        <param name="jobDeleteOptions">
            <span data-ttu-id="7dbaf-135">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-135">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-137">ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-137">Deletes a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-138">ジョブを削除すると、そのジョブの一部であるすべてのタスクとすべてのジョブの統計も削除されます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-138">Deleting a job also deletes all tasks that are part of that job, and all job statistics.</span></span> <span data-ttu-id="7dbaf-139">タスクのデータの保有期間も上書きされます。つまり、ジョブにコンピューティング ノードで保持されているタスクが含まれている場合、バッチ サービスをそれらのタスクの作業ディレクトリとそのすべてのコンテンツを削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-139">This also overrides the retention period for task data; that is, if the job contains tasks which are still retained on compute nodes, the Batch services deletes those tasks' working directories and all their contents.</span></span>  <span data-ttu-id="7dbaf-140">ジョブの削除要求を受信すると、バッチ サービスは、削除の状態にジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-140">When a Delete Job request is received, the Batch service sets the job to the deleting state.</span></span> <span data-ttu-id="7dbaf-141">ジョブの状態を削除するのには上のすべての更新操作は、追加情報をジョブが削除されていることを示すステータス コード 409 (Conflict) で失敗します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-141">All update operations on a job that is in deleting state will fail with status code 409 (Conflict), with additional information indicating that the job is being deleted.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders Disable (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders Disable(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Disable(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions)" />
      <MemberSignature Language="F#" Value="static member Disable : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Disable (operations, jobId, disableTasks, jobDisableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-142">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-143">無効にするジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-143">The ID of the job to disable.</span></span>
            </param>
        <param name="disableTasks">
            <span data-ttu-id="7dbaf-144">ジョブに関連付けられているアクティブなタスクを行うには何か。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-144">What to do with active tasks associated with the job.</span></span> <span data-ttu-id="7dbaf-145">使用可能な値が含まれます: 'キューに再登録'、'終了'、'待機'</span><span class="sxs-lookup"><span data-stu-id="7dbaf-145">Possible values include: 'requeue', 'terminate', 'wait'</span></span>
            </param>
        <param name="jobDisableOptions">
            <span data-ttu-id="7dbaf-146">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-146">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-147">新しいタスクの実行を妨げて、指定されたジョブを無効にします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-147">Disables the specified job, preventing new tasks from running.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-148">すぐに、Batch Service はジョブを無効化の状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-148">The Batch Service immediately moves the job to the disabling state.</span></span> <span data-ttu-id="7dbaf-149">バッチは、この disableTasks パラメーターを使用して、ジョブの現在実行中のタスクを行うには何かを判断します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-149">Batch then uses the disableTasks parameter to determine what to do with the currently running tasks of the job.</span></span> <span data-ttu-id="7dbaf-150">ジョブ状態のまま残す無効にすると無効化操作が完了し、すべてのタスクが処理済み disableTasks オプション; に基づいてまでジョブは、無効の状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-150">The job remains in the disabling state until the disable operation is completed and all tasks have been dealt with according to the disableTasks option; the job then moves to the disabled state.</span></span> <span data-ttu-id="7dbaf-151">コンソール アプリケーションは、アクティブな状態に戻るまで、ジョブの下で、新しいタスクは開始されません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-151">No new tasks are started under the job until it moves back to active state.</span></span> <span data-ttu-id="7dbaf-152">Active 以外の任意の状態になっているジョブを無効にしようとすると、無効化または無効にされた、要求が失敗したステータス コード 409 でします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-152">If you try to disable a job that is in any state other than active, disabling, or disabled, the request fails with status code 409.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt; DisableAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt; DisableAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DisableAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.DisableAsync (operations, jobId, disableTasks, jobDisableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;DisableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-153">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-154">無効にするジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-154">The ID of the job to disable.</span></span>
            </param>
        <param name="disableTasks">
            <span data-ttu-id="7dbaf-155">ジョブに関連付けられているアクティブなタスクを行うには何か。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-155">What to do with active tasks associated with the job.</span></span> <span data-ttu-id="7dbaf-156">使用可能な値が含まれます: 'キューに再登録'、'終了'、'待機'</span><span class="sxs-lookup"><span data-stu-id="7dbaf-156">Possible values include: 'requeue', 'terminate', 'wait'</span></span>
            </param>
        <param name="jobDisableOptions">
            <span data-ttu-id="7dbaf-157">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-157">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-159">新しいタスクの実行を妨げて、指定されたジョブを無効にします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-159">Disables the specified job, preventing new tasks from running.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-160">すぐに、Batch Service はジョブを無効化の状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-160">The Batch Service immediately moves the job to the disabling state.</span></span> <span data-ttu-id="7dbaf-161">バッチは、この disableTasks パラメーターを使用して、ジョブの現在実行中のタスクを行うには何かを判断します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-161">Batch then uses the disableTasks parameter to determine what to do with the currently running tasks of the job.</span></span> <span data-ttu-id="7dbaf-162">ジョブ状態のまま残す無効にすると無効化操作が完了し、すべてのタスクが処理済み disableTasks オプション; に基づいてまでジョブは、無効の状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-162">The job remains in the disabling state until the disable operation is completed and all tasks have been dealt with according to the disableTasks option; the job then moves to the disabled state.</span></span> <span data-ttu-id="7dbaf-163">コンソール アプリケーションは、アクティブな状態に戻るまで、ジョブの下で、新しいタスクは開始されません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-163">No new tasks are started under the job until it moves back to active state.</span></span> <span data-ttu-id="7dbaf-164">Active 以外の任意の状態になっているジョブを無効にしようとすると、無効化または無効にされた、要求が失敗したステータス コード 409 でします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-164">If you try to disable a job that is in any state other than active, disabling, or disabled, the request fails with status code 409.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders Enable (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders Enable(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Enable(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions)" />
      <MemberSignature Language="F#" Value="static member Enable : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Enable (operations, jobId, jobEnableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-165">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-166">有効にするジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-166">The ID of the job to enable.</span></span>
            </param>
        <param name="jobEnableOptions">
            <span data-ttu-id="7dbaf-167">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-167">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-168">新しいタスクの実行を許可する、指定されたジョブを有効にします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-168">Enables the specified job, allowing new tasks to run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-169">この API を呼び出すときに、バッチ サービスは、有効にすると、状態を無効になっているジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-169">When you call this API, the Batch service sets a disabled job to the enabling state.</span></span> <span data-ttu-id="7dbaf-170">この後、ジョブはアクティブ状態、およびジョブの再開での新しいタスクのスケジュール に移動操作を完了すると、します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-170">After the this operation is completed, the job moves to the active state, and scheduling of new tasks under the job resumes.</span></span> <span data-ttu-id="7dbaf-171">バッチ サービスでは、7 日間を超えてアクティブ状態のままにして、タスクは許可されません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-171">The Batch service does not allow a task to remain in the active state for more than 7 days.</span></span> <span data-ttu-id="7dbaf-172">そのため、7 日以上前に追加されたアクティブなタスクを含むジョブを有効にすると、それらのタスクは実行されません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-172">Therefore, if you enable a job containing active tasks which were added more than 7 days ago, those tasks will not run.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt; EnableAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt; EnableAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.EnableAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.EnableAsync (operations, jobId, jobEnableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;EnableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-173">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-174">有効にするジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-174">The ID of the job to enable.</span></span>
            </param>
        <param name="jobEnableOptions">
            <span data-ttu-id="7dbaf-175">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-175">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-177">新しいタスクの実行を許可する、指定されたジョブを有効にします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-177">Enables the specified job, allowing new tasks to run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-178">この API を呼び出すときに、バッチ サービスは、有効にすると、状態を無効になっているジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-178">When you call this API, the Batch service sets a disabled job to the enabling state.</span></span> <span data-ttu-id="7dbaf-179">この後、ジョブはアクティブ状態、およびジョブの再開での新しいタスクのスケジュール に移動操作を完了すると、します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-179">After the this operation is completed, the job moves to the active state, and scheduling of new tasks under the job resumes.</span></span> <span data-ttu-id="7dbaf-180">バッチ サービスでは、7 日間を超えてアクティブ状態のままにして、タスクは許可されません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-180">The Batch service does not allow a task to remain in the active state for more than 7 days.</span></span> <span data-ttu-id="7dbaf-181">そのため、7 日以上前に追加されたアクティブなタスクを含むジョブを有効にすると、それらのタスクは実行されません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-181">Therefore, if you enable a job containing active tasks which were added more than 7 days ago, those tasks will not run.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudJob Get (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudJob Get(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJob" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Get (operations, jobId, jobGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-182">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-183">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-183">The ID of the job.</span></span>
            </param>
        <param name="jobGetOptions">
            <span data-ttu-id="7dbaf-184">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-184">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-185">指定したジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-185">Gets information about the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobStatistics GetAllLifetimeStatistics (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobStatistics GetAllLifetimeStatistics(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatistics(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatistics : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobStatistics" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatistics (operations, jobGetAllLifetimeStatisticsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-186">The operations group for this extension method.</span></span>
            </param>
        <param name="jobGetAllLifetimeStatisticsOptions">
            <span data-ttu-id="7dbaf-187">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-187">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-188">指定されたアカウント内のジョブのすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-188">Gets lifetime summary statistics for all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-189">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-189">Statistics are aggregated across all jobs that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt; GetAllLifetimeStatisticsAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt; GetAllLifetimeStatisticsAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatisticsAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatisticsAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAllLifetimeStatisticsAsync (operations, jobGetAllLifetimeStatisticsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetAllLifetimeStatisticsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-190">The operations group for this extension method.</span></span>
            </param>
        <param name="jobGetAllLifetimeStatisticsOptions">
            <span data-ttu-id="7dbaf-191">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-191">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-193">指定されたアカウント内のジョブのすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-193">Gets lifetime summary statistics for all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-194">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-194">Statistics are aggregated across all jobs that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetAsync (operations, jobId, jobGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-195">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-196">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-196">The ID of the job.</span></span>
            </param>
        <param name="jobGetOptions">
            <span data-ttu-id="7dbaf-197">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-197">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-199">指定したジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-199">Gets information about the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCounts">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskCounts GetTaskCounts (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskCounts GetTaskCounts(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCounts(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions)" />
      <MemberSignature Language="F#" Value="static member GetTaskCounts : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskCounts" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCounts (operations, jobId, jobGetTaskCountsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskCounts</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-200">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-200">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-201">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-201">The ID of the job.</span></span>
            </param>
        <param name="jobGetTaskCountsOptions">
            <span data-ttu-id="7dbaf-202">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-202">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-203">指定されたジョブのタスクの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-203">Gets the task counts for the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-204">タスクの数は、アクティブな実行中または完了したタスクの状態によって、タスクの数と、成功または失敗したタスクの数を提供します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-204">Task counts provide a count of the tasks by active, running or completed task state, and a count of tasks which succeeded or failed.</span></span> <span data-ttu-id="7dbaf-205">準備状態のタスクが実行中としてカウントされます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-205">Tasks in the preparing state are counted as running.</span></span> <span data-ttu-id="7dbaf-206">ValidationStatus が検証済みでない場合、Batch サービスがされていませんリスト タスク API で報告されるタスクの状態に対して状態の数を確認できません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-206">If the validationStatus is unvalidated, then the Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span> <span data-ttu-id="7dbaf-207">ジョブには、200,000 以上のタスクが含まれている場合に、validationStatus を検証できない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-207">The validationStatus may be unvalidated if the job contains more than 200,000 tasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt; GetTaskCountsAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt; GetTaskCountsAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCountsAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTaskCountsAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.GetTaskCountsAsync (operations, jobId, jobGetTaskCountsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;GetTaskCountsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-208">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-209">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-209">The ID of the job.</span></span>
            </param>
        <param name="jobGetTaskCountsOptions">
            <span data-ttu-id="7dbaf-210">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-210">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-212">指定されたジョブのタスクの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-212">Gets the task counts for the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-213">タスクの数は、アクティブな実行中または完了したタスクの状態によって、タスクの数と、成功または失敗したタスクの数を提供します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-213">Task counts provide a count of the tasks by active, running or completed task state, and a count of tasks which succeeded or failed.</span></span> <span data-ttu-id="7dbaf-214">準備状態のタスクが実行中としてカウントされます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-214">Tasks in the preparing state are counted as running.</span></span> <span data-ttu-id="7dbaf-215">ValidationStatus が検証済みでない場合、Batch サービスがされていませんリスト タスク API で報告されるタスクの状態に対して状態の数を確認できません。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-215">If the validationStatus is unvalidated, then the Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span> <span data-ttu-id="7dbaf-216">ジョブには、200,000 以上のタスクが含まれている場合に、validationStatus を検証できない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-216">The validationStatus may be unvalidated if the job contains more than 200,000 tasks.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; List (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; List(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.List (operations, jobListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-217">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-217">The operations group for this extension method.</span></span>
            </param>
        <param name="jobListOptions">
            <span data-ttu-id="7dbaf-218">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-218">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-219">指定されたアカウント内のジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-219">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,Microsoft.Azure.Batch.Protocol.Models.JobListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * Microsoft.Azure.Batch.Protocol.Models.JobListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListAsync (operations, jobListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-220">The operations group for this extension method.</span></span>
            </param>
        <param name="jobListOptions">
            <span data-ttu-id="7dbaf-221">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-221">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-223">指定されたアカウント内のジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-223">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobSchedule">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobSchedule (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobSchedule(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobSchedule(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromJobSchedule : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobSchedule (operations, jobScheduleId, jobListFromJobScheduleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-224">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-224">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="7dbaf-225">ジョブの一覧を取得するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-225">The ID of the job schedule from which you want to get a list of jobs.</span></span>
            </param>
        <param name="jobListFromJobScheduleOptions">
            <span data-ttu-id="7dbaf-226">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-226">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-227">指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-227">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleAsync (operations, jobScheduleId, jobListFromJobScheduleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListFromJobScheduleAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-228">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="7dbaf-229">ジョブの一覧を取得するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-229">The ID of the job schedule from which you want to get a list of jobs.</span></span>
            </param>
        <param name="jobListFromJobScheduleOptions">
            <span data-ttu-id="7dbaf-230">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-230">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-232">指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-232">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobScheduleNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListFromJobScheduleNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNext (operations, nextPageLink, jobListFromJobScheduleNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-233">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7dbaf-234">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-234">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            <span data-ttu-id="7dbaf-235">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-235">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-236">指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-236">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFromJobScheduleNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListFromJobScheduleNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFromJobScheduleNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListFromJobScheduleNextAsync (operations, nextPageLink, jobListFromJobScheduleNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListFromJobScheduleNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-237">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-237">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7dbaf-238">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-238">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            <span data-ttu-id="7dbaf-239">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-239">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-241">指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-241">Lists the jobs that have been created under the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNext (operations, nextPageLink, jobListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-242">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7dbaf-243">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-243">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListNextOptions">
            <span data-ttu-id="7dbaf-244">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-244">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-245">指定されたアカウント内のジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-245">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListNextAsync (operations, nextPageLink, jobListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-246">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-246">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7dbaf-247">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-247">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListNextOptions">
            <span data-ttu-id="7dbaf-248">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-248">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-250">指定されたアカウント内のジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-250">Lists all of the jobs in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatus (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatus(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatus(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatus : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatus (operations, jobId, jobListPreparationAndReleaseTaskStatusOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-251">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-252">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-252">The ID of the job.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            <span data-ttu-id="7dbaf-253">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-253">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-254">ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-254">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-255">この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-255">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="7dbaf-256">これには、プールからからは削除されているノードが含まれます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-256">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="7dbaf-257">この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-257">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusAsync (operations, jobId, jobListPreparationAndReleaseTaskStatusOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListPreparationAndReleaseTaskStatusAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-258">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-258">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-259">ジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-259">The ID of the job.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            <span data-ttu-id="7dbaf-260">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-260">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-261">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-261">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-262">ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-262">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-263">この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-263">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="7dbaf-264">これには、プールからからは削除されているノードが含まれます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-264">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="7dbaf-265">この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-265">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatusNext (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt; ListPreparationAndReleaseTaskStatusNext(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNext(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusNext : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNext (operations, nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-266">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-266">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7dbaf-267">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-267">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            <span data-ttu-id="7dbaf-268">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-268">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-269">ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-269">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-270">この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-270">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="7dbaf-271">これには、プールからからは削除されているノードが含まれます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-271">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="7dbaf-272">この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-272">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPreparationAndReleaseTaskStatusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusNextAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt; ListPreparationAndReleaseTaskStatusNextAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNextAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPreparationAndReleaseTaskStatusNextAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.ListPreparationAndReleaseTaskStatusNextAsync (operations, nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;ListPreparationAndReleaseTaskStatusNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-273">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7dbaf-274">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-274">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            <span data-ttu-id="7dbaf-275">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-275">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-276">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-277">ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-277">Lists the execution status of the Job Preparation and Job Release task for the specified job across the compute nodes where the job has run.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-278">この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-278">This API returns the Job Preparation and Job Release task status on all compute nodes that have run the Job Preparation or Job Release task.</span></span> <span data-ttu-id="7dbaf-279">これには、プールからからは削除されているノードが含まれます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-279">This includes nodes which have since been removed from the pool.</span></span> <span data-ttu-id="7dbaf-280">この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-280">If this API is invoked on a job which has no Job Preparation or Job Release task, the Batch service returns HTTP status code 409 (Conflict) with an error code of JobPreparationTaskNotSpecified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders Patch (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders Patch(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Patch(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions)" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Patch (operations, jobId, jobPatchParameter, jobPatchOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-281">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-281">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-282">プロパティを更新するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-282">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobPatchParameter">
            <span data-ttu-id="7dbaf-283">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-283">The parameters for the request.</span></span>
            </param>
        <param name="jobPatchOptions">
            <span data-ttu-id="7dbaf-284">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-284">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-285">指定したジョブのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-285">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-286">これには、要求で指定されたジョブのプロパティのみが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-286">This replaces only the job properties specified in the request.</span></span> <span data-ttu-id="7dbaf-287">たとえば、ジョブの制約には、要求が制約要素を指定しない場合は、既存の制約維持ジョブにします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-287">For example, if the job has constraints, and a request does not specify the constraints element, then the job keeps the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt; PatchAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt; PatchAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.PatchAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.PatchAsync (operations, jobId, jobPatchParameter, jobPatchOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;PatchAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-288">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-288">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-289">プロパティを更新するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-289">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobPatchParameter">
            <span data-ttu-id="7dbaf-290">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-290">The parameters for the request.</span></span>
            </param>
        <param name="jobPatchOptions">
            <span data-ttu-id="7dbaf-291">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-291">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-292">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-292">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-293">指定したジョブのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-293">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-294">これには、要求で指定されたジョブのプロパティのみが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-294">This replaces only the job properties specified in the request.</span></span> <span data-ttu-id="7dbaf-295">たとえば、ジョブの制約には、要求が制約要素を指定しない場合は、既存の制約維持ジョブにします。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-295">For example, if the job has constraints, and a request does not specify the constraints element, then the job keeps the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.IJobOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Terminate (operations, jobId, terminateReason, jobTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-296">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-297">終了するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-297">The ID of the job to terminate.</span></span>
            </param>
        <param name="terminateReason">
            <span data-ttu-id="7dbaf-298">ジョブの TerminateReason として表示するテキストです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-298">The text you want to appear as the job's TerminateReason.</span></span> <span data-ttu-id="7dbaf-299">既定値は、'UserTerminate' です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-299">The default is 'UserTerminate'.</span></span>
            </param>
        <param name="jobTerminateOptions">
            <span data-ttu-id="7dbaf-300">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-300">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-301">完了としてマークして、指定されたジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-301">Terminates the specified job, marking it as completed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-302">ジョブの終了要求を受信すると、Batch service はジョブを最終状態に設定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-302">When a Terminate Job request is received, the Batch service sets the job to the terminating state.</span></span> <span data-ttu-id="7dbaf-303">バッチ サービスは、ジョブに関連付けられているアクティブなまたは実行中のタスクを終了し、必要なジョブのリリース タスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-303">The Batch service then terminates any active or running tasks associated with the job, and runs any required Job Release tasks.</span></span> <span data-ttu-id="7dbaf-304">ジョブは、完了した状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-304">The job then moves into the completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.TerminateAsync (operations, jobId, terminateReason, jobTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-305">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-305">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-306">終了するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-306">The ID of the job to terminate.</span></span>
            </param>
        <param name="terminateReason">
            <span data-ttu-id="7dbaf-307">ジョブの TerminateReason として表示するテキストです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-307">The text you want to appear as the job's TerminateReason.</span></span> <span data-ttu-id="7dbaf-308">既定値は、'UserTerminate' です。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-308">The default is 'UserTerminate'.</span></span>
            </param>
        <param name="jobTerminateOptions">
            <span data-ttu-id="7dbaf-309">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-309">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-310">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-311">完了としてマークして、指定されたジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-311">Terminates the specified job, marking it as completed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-312">ジョブの終了要求を受信すると、Batch service はジョブを最終状態に設定します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-312">When a Terminate Job request is received, the Batch service sets the job to the terminating state.</span></span> <span data-ttu-id="7dbaf-313">バッチ サービスは、ジョブに関連付けられているアクティブなまたは実行中のタスクを終了し、必要なジョブのリリース タスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-313">The Batch service then terminates any active or running tasks associated with the job, and runs any required Job Release tasks.</span></span> <span data-ttu-id="7dbaf-314">ジョブは、完了した状態に移動します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-314">The job then moves into the completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.Update (operations, jobId, jobUpdateParameter, jobUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-315">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-315">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-316">プロパティを更新するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-316">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobUpdateParameter">
            <span data-ttu-id="7dbaf-317">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-317">The parameters for the request.</span></span>
            </param>
        <param name="jobUpdateOptions">
            <span data-ttu-id="7dbaf-318">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-318">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-319">指定したジョブのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-319">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-320">これにより、ジョブのすべての更新可能なプロパティが完全に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-320">This fully replaces all the updateable properties of the job.</span></span> <span data-ttu-id="7dbaf-321">たとえば、ジョブに関連付けられている制約が設定されている場合、この要求に制約が指定されていない場合、Batch service、既存の制約は削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-321">For example, if the job has constraints associated with it and if constraints is not specified with this request, then the Batch service will remove the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.IJobOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.IJobOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.IJobOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobOperationsExtensions.UpdateAsync (operations, jobId, jobUpdateParameter, jobUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7dbaf-322">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-322">The operations group for this extension method.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7dbaf-323">プロパティを更新するジョブの ID。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-323">The ID of the job whose properties you want to update.</span></span>
            </param>
        <param name="jobUpdateParameter">
            <span data-ttu-id="7dbaf-324">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-324">The parameters for the request.</span></span>
            </param>
        <param name="jobUpdateOptions">
            <span data-ttu-id="7dbaf-325">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="7dbaf-325">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbaf-326">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbaf-327">指定したジョブのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-327">Updates the properties of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbaf-328">これにより、ジョブのすべての更新可能なプロパティが完全に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-328">This fully replaces all the updateable properties of the job.</span></span> <span data-ttu-id="7dbaf-329">たとえば、ジョブに関連付けられている制約が設定されている場合、この要求に制約が指定されていない場合、Batch service、既存の制約は削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbaf-329">For example, if the job has constraints associated with it and if constraints is not specified with this request, then the Batch service will remove the existing constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>