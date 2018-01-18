<Type Name="JobReleaseTaskExecutionInformation" FullName="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobReleaseTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobReleaseTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobReleaseTaskExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="bd743-101">実行に関する詳細、<see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask">ジョブのリリース タスク</see>コンピューティング ノード上でします。</span><span class="sxs-lookup"><span data-stu-id="bd743-101">Details about the execution of a <see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask">Job Release task</see> on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ContainerInformation" />
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
            <span data-ttu-id="bd743-102">タスクを実行しているコンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-102">Gets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bd743-103">タスクがコンテナーのコンテキストで実行している場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="bd743-103">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.EndTime" />
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
            <span data-ttu-id="bd743-104">タスクが完了した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-104">Gets the time at which the task completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bd743-105">このプロパティはタスクがの場合にのみ返されます、<see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="bd743-105">This property is only returned if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" /> state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.ExitCode" />
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
            <span data-ttu-id="bd743-106">タスクのコマンドラインで指定されたプログラムの終了コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-106">Gets the exit code of the program specified on the task command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bd743-107">このプロパティはタスクがの場合にのみ返されます、<see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="bd743-107">This property is only returned if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" /> state.</span></span> <span data-ttu-id="bd743-108">プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。</span><span class="sxs-lookup"><span data-stu-id="bd743-108">The exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="bd743-109">意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="bd743-109">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="bd743-110">終了コードがコンピューティング ノードなど、オペレーティング システム、プロセスを強制的に終了する場合に生成される可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="bd743-110">Note that the exit code may also be generated by the compute node operating system, such as when a process is forcibly terminated.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.FailureInformation" />
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
            <span data-ttu-id="bd743-111">存在する場合、タスクの失敗の記述を情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-111">Gets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bd743-112">タスクがである場合にのみ、このプロパティは設定、<see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" />状態にあり、エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="bd743-112">This property is set only if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.JobReleaseTaskState.Completed" /> state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.Result" />
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
            <span data-ttu-id="bd743-113">タスクの実行の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-113">Gets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bd743-114">値が場合<see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />、エラーの詳細は含まれてし、<see cref="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.FailureInformation" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="bd743-114">If the value is <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, then the details of the failure can be found in the <see cref="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.FailureInformation" /> property.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd743-115">タスクが実行を開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-115">Gets the time at which the task started running.</span></span> <span data-ttu-id="bd743-116">タスクが再起動されるたびに、この値を更新することを注意してください。</span><span class="sxs-lookup"><span data-stu-id="bd743-116">Note that every time the task is restarted, this value is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.JobReleaseTaskState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.JobReleaseTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As JobReleaseTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Common.JobReleaseTaskState" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobReleaseTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd743-117">タスクの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-117">Gets the current state of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bd743-118">タスクが現在実行されていることを意味を実行します。</span><span class="sxs-lookup"><span data-stu-id="bd743-118">Running means the task is currently running.</span></span> <span data-ttu-id="bd743-119">完了したことを意味するタスクが完了しました。</span><span class="sxs-lookup"><span data-stu-id="bd743-119">Completed means the task has completed.</span></span> <span data-ttu-id="bd743-120">完了済みの状態は、タスクが正常に終了コード 0 で終了する場合と、システムがスケジュール エラーのためのタスク プロセスの起動に失敗した場合やさまざまなタスクが失敗した後、再試行の上限に達しました場合は、含まれています。</span><span class="sxs-lookup"><span data-stu-id="bd743-120">The Completed state includes the case where the task exits successfully with exit code 0 and the cases where the system fails to start the task process due to scheduling errors or the retry limit has reached after numerous task failures.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectory">
      <MemberSignature Language="C#" Value="public string TaskRootDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRootDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectory : string" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd743-121">コンピューティング ノードでジョブのリリース タスクのルート ディレクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-121">Gets the root directory of the Job Release task on the compute node.</span></span> <span data-ttu-id="bd743-122">このパスを使用すると、ログ ファイルなど、タスクによって作成されたファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-122">You can use this path to retrieve files created by the task, such as log files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectoryUrl">
      <MemberSignature Language="C#" Value="public string TaskRootDirectoryUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRootDirectoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectoryUrl : string" Usage="Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd743-123">コンピューティング ノードでジョブのリリース タスクのルート ディレクトリへの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd743-123">Gets the URL to the root directory of the Job Release task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>