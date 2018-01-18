<Type Name="TaskExecutionInformation" FullName="Microsoft.Azure.Batch.TaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class TaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type TaskExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="6949b-101">タスクの実行情報。</span><span class="sxs-lookup"><span data-stu-id="6949b-101">Task execution information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.ContainerInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-102">タスクを実行しているコンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-102">Gets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6949b-103">タスクがコンテナーのコンテキストで実行している場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="6949b-103">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-104">タスクが完了した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-104">Gets the time at which the task completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-105">タスクのコマンドラインで指定されたプログラムの終了コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-105">Gets the exit code of the program specified on the task command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6949b-106">このプロパティはタスクがの場合にのみ返されます、<see cref="F:Microsoft.Azure.Batch.Common.TaskState.Completed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="6949b-106">This property is only returned if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.TaskState.Completed" /> state.</span></span> <span data-ttu-id="6949b-107">プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。</span><span class="sxs-lookup"><span data-stu-id="6949b-107">The exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="6949b-108">意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="6949b-108">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="6949b-109">終了コードがコンピューティング ノードなど、オペレーティング システム、プロセスを強制的に終了する場合に生成される可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="6949b-109">Note that the exit code may also be generated by the compute node operating system, such as when a process is forcibly terminated.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.FailureInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-110">存在する場合、タスクの失敗の記述を情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-110">Gets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6949b-111">タスクがである場合にのみ、このプロパティは設定、<see cref="F:Microsoft.Azure.Batch.Common.TaskState.Completed" />状態にあり、エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="6949b-111">This property is set only if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.TaskState.Completed" /> state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRequeueTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRequeueTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRequeueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.LastRequeueTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRequeueTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRequeueTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.LastRequeueTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-112">このタスクの実行が再びキューにユーザー要求ごとに、Batch service によって最新の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-112">Gets the most recent time at which this task's execution was re-queued by the Batch service per user request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.LastRetryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-113">このタスクの実行が Batch service によって再試行された最新の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-113">Gets the most recent time at which this task's execution was retried by the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequeueCount">
      <MemberSignature Language="C#" Value="public int RequeueCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.RequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RequeueCount : int" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.RequeueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-114">ユーザー要求ごとに、Batch service によってこのタスクの実行がキューに再回数を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-114">Gets the number of times this task's execution was re-queued by the Batch service per user request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-115">タスクの実行の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-115">Gets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6949b-116">値が場合<see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />、エラーの詳細は含まれてし、<see cref="P:Microsoft.Azure.Batch.TaskExecutionInformation.FailureInformation" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="6949b-116">If the value is <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, then the details of the failure can be found in the <see cref="P:Microsoft.Azure.Batch.TaskExecutionInformation.FailureInformation" /> property.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.RetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-117">タスクが、Batch service によって再試行された回数を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-117">Gets the number of times the task has been retried by the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6949b-118">タスクのアプリケーション エラー (0 以外の終了コード) は再試行処理前のエラー (タスクを実行できませんでした) され、ファイルのアップロード エラーは再試行されません。</span><span class="sxs-lookup"><span data-stu-id="6949b-118">Task application failures (non-zero exit code) are retried, pre-processing errors (the task could not be run) and file upload errors are not retried.</span></span> <span data-ttu-id="6949b-119">バッチ サービスは、指定されたタスクを再試行<see cref="P:Microsoft.Azure.Batch.TaskConstraints.MaxTaskRetryCount" />です。</span><span class="sxs-lookup"><span data-stu-id="6949b-119">The Batch service will retry the task up to the specified <see cref="P:Microsoft.Azure.Batch.TaskConstraints.MaxTaskRetryCount" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.TaskExecutionInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6949b-120">タスクが実行を開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="6949b-120">Gets the time at which the task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>