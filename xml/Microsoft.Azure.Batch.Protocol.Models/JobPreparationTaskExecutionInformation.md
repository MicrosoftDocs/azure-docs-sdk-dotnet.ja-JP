<Type Name="JobPreparationTaskExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobPreparationTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobPreparationTaskExecutionInformation = class" />
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
            <span data-ttu-id="d3851-101">コンピューティング ノードでジョブの準備タスクの実行に関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="d3851-101">Contains information about the execution of a Job Preparation task on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTaskExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3851-102">JobPreparationTaskExecutionInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3851-102">Initializes a new instance of the JobPreparationTaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTaskExecutionInformation (DateTime startTime, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState state, int retryCount, Nullable&lt;DateTime&gt; endTime = null, string taskRootDirectory = null, string taskRootDirectoryUrl = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;DateTime&gt; lastRetryTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState state, int32 retryCount, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string taskRootDirectory, string taskRootDirectoryUrl, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRetryTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.#ctor(System.DateTime,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState,System.Int32,System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, state As JobPreparationTaskState, retryCount As Integer, Optional endTime As Nullable(Of DateTime) = null, Optional taskRootDirectory As String = null, Optional taskRootDirectoryUrl As String = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional lastRetryTime As Nullable(Of DateTime) = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation : DateTime * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState * int * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation (startTime, state, retryCount, endTime, taskRootDirectory, taskRootDirectoryUrl, exitCode, containerInfo, failureInfo, lastRetryTime, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="state" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState" />
        <Parameter Name="retryCount" Type="System.Int32" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="taskRootDirectory" Type="System.String" />
        <Parameter Name="taskRootDirectoryUrl" Type="System.String" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="lastRetryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="d3851-103">タスクの実行が開始した時刻です。</span><span class="sxs-lookup"><span data-stu-id="d3851-103">The time at which the task started running.</span></span></param>
        <param name="state"><span data-ttu-id="d3851-104">コンピューティング ノードでジョブの準備タスクの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="d3851-104">The current state of the Job Preparation task on the compute node.</span></span></param>
        <param name="retryCount"><span data-ttu-id="d3851-105">Batch サービスによりタスクが再試行された回数。</span><span class="sxs-lookup"><span data-stu-id="d3851-105">The number of times the task has been retried by the Batch service.</span></span> <span data-ttu-id="d3851-106">タスクのアプリケーション エラー (0 以外の終了コード) は再試行処理前のエラー (タスクを実行できませんでした) され、ファイルのアップロード エラーは再試行されません。</span><span class="sxs-lookup"><span data-stu-id="d3851-106">Task application failures (non-zero exit code) are retried, pre-processing errors (the task could not be run) and file upload errors are not retried.</span></span> <span data-ttu-id="d3851-107">バッチ サービスは、制約で指定された上限に達するまでタスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="d3851-107">The Batch service will retry the task up to the limit specified by the constraints.</span></span></param>
        <param name="endTime"><span data-ttu-id="d3851-108">ジョブの準備タスクが完了した時刻。</span><span class="sxs-lookup"><span data-stu-id="d3851-108">The time at which the Job Preparation task completed.</span></span></param>
        <param name="taskRootDirectory"><span data-ttu-id="d3851-109">コンピューティング ノードでジョブの準備タスクのルート ディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="d3851-109">The root directory of the Job Preparation task on the compute node.</span></span> <span data-ttu-id="d3851-110">このパスを使用すると、ログ ファイルなど、タスクによって作成されたファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3851-110">You can use this path to retrieve files created by the task, such as log files.</span></span></param>
        <param name="taskRootDirectoryUrl"><span data-ttu-id="d3851-111">コンピューティング ノードでジョブの準備タスクのルート ディレクトリの URL です。</span><span class="sxs-lookup"><span data-stu-id="d3851-111">The URL to the root directory of the Job Preparation task on the compute node.</span></span></param>
        <param name="exitCode"><span data-ttu-id="d3851-112">タスクのコマンドラインで指定されたプログラムの終了コード。</span><span class="sxs-lookup"><span data-stu-id="d3851-112">The exit code of the program specified on the task command line.</span></span></param>
        <param name="containerInfo"><span data-ttu-id="d3851-113">タスクを実行しているコンテナーについて説明します。</span><span class="sxs-lookup"><span data-stu-id="d3851-113">Information about the container under which the task is executing.</span></span></param>
        <param name="failureInfo"><span data-ttu-id="d3851-114">存在する場合、タスクの失敗を説明する情報です。</span><span class="sxs-lookup"><span data-stu-id="d3851-114">Information describing the task failure, if any.</span></span></param>
        <param name="lastRetryTime"><span data-ttu-id="d3851-115">ジョブの準備タスクの再試行が実行を開始する最新の時間。</span><span class="sxs-lookup"><span data-stu-id="d3851-115">The most recent time at which a retry of the Job Preparation task started running.</span></span></param>
        <param name="result"><span data-ttu-id="d3851-116">タスクの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="d3851-116">The result of the task execution.</span></span></param>
        <summary>
            <span data-ttu-id="d3851-117">JobPreparationTaskExecutionInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3851-117">Initializes a new instance of the JobPreparationTaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.ContainerInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-118">取得またはタスクを実行しているコンテナーに関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-118">Gets or sets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-119">タスクがコンテナーのコンテキストで実行している場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="d3851-119">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-120">取得またはジョブの準備タスクが完了した時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-120">Gets or sets the time at which the Job Preparation task completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-121">タスクが完了済みの状態の場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="d3851-121">This property is set only if the task is in the Completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-122">取得またはタスクのコマンドラインで指定されたプログラムの終了コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-122">Gets or sets the exit code of the program specified on the task command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-123">このパラメーターには、タスクが完了した状態の場合にのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="d3851-123">This parameter is returned only if the task is in the completed state.</span></span> <span data-ttu-id="d3851-124">プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。</span><span class="sxs-lookup"><span data-stu-id="d3851-124">The exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="d3851-125">意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="d3851-125">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="d3851-126">終了コードがコンピューティング ノードなど、オペレーティング システム、プロセスを強制的に終了する場合に生成される可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d3851-126">Note that the exit code may also be generated by the compute node operating system, such as when a process is forcibly terminated.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.FailureInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failureInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-127">取得または存在する場合に、タスクの失敗を示す情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-127">Gets or sets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-128">このプロパティは、タスクが完了した状態の場合にのみ設定され、エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="d3851-128">This property is set only if the task is in the completed state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.LastRetryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRetryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-129">取得または最新のジョブの準備タスクの再試行が実行を開始する時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-129">Gets or sets the most recent time at which a retry of the Job Preparation task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-130">タスクが再試行された場合にのみ、このプロパティが設定 (つまり retryCount が 0 以外)。</span><span class="sxs-lookup"><span data-stu-id="d3851-130">This property is set only if the task was retried (i.e. retryCount is nonzero).</span></span> <span data-ttu-id="d3851-131">存在する場合、これは通常、開始時刻と同じですが再試行; 以外の理由により、タスクが再起動された場合は異なる場合があります。たとえば、再試行中にコンピューティング ノードを再起動すると場合、startTime が更新されますが、lastRetryTime はありません。</span><span class="sxs-lookup"><span data-stu-id="d3851-131">If present, this is typically the same as startTime, but may be different if the task has been restarted for reasons other than retry; for example, if the compute node was rebooted during a retry, then the startTime is updated but the lastRetryTime is not.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-132">取得またはタスクの実行の結果を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-132">Gets or sets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-133">場合は、値は '失敗'、エラーの詳細は failureInfo プロパティで確認できます。</span><span class="sxs-lookup"><span data-stu-id="d3851-133">If the value is 'failed', then the details of the failure can be found in the failureInfo property.</span></span> <span data-ttu-id="d3851-134">使用可能な値が含まれます: 'は success'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="d3851-134">Possible values include: 'success', 'failure'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.RetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-135">取得またはタスクが、Batch service によって再試行された回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-135">Gets or sets the number of times the task has been retried by the Batch service.</span></span> <span data-ttu-id="d3851-136">タスクのアプリケーション エラー (0 以外の終了コード) は再試行処理前のエラー (タスクを実行できませんでした) され、ファイルのアップロード エラーは再試行されません。</span><span class="sxs-lookup"><span data-stu-id="d3851-136">Task application failures (non-zero exit code) are retried, pre-processing errors (the task could not be run) and file upload errors are not retried.</span></span> <span data-ttu-id="d3851-137">バッチ サービスは、制約で指定された上限に達するまでタスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="d3851-137">The Batch service will retry the task up to the limit specified by the constraints.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-138">タスクのアプリケーション エラー (0 以外の終了コード) は再試行処理前のエラー (タスクを実行できませんでした) され、ファイルのアップロード エラーは再試行されません。</span><span class="sxs-lookup"><span data-stu-id="d3851-138">Task application failures (non-zero exit code) are retried, pre-processing errors (the task could not be run) and file upload errors are not retried.</span></span> <span data-ttu-id="d3851-139">バッチ サービスは、制約で指定された上限に達するまでタスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="d3851-139">The Batch service will retry the task up to the limit specified by the constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-140">取得またはタスクが実行を開始された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-140">Gets or sets the time at which the task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-141">タスクが再起動または再実行された場合は、タスクが実行を開始したつい最近の時刻となります。</span><span class="sxs-lookup"><span data-stu-id="d3851-141">If the task has been restarted or retried, this is the most recent time at which the task started running.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As JobPreparationTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-142">取得または計算ノードでジョブの準備タスクの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-142">Gets or sets the current state of the Job Preparation task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d3851-143">使用可能な値が含まれます: 'を実行している'、'完了'</span><span class="sxs-lookup"><span data-stu-id="d3851-143">Possible values include: 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectory">
      <MemberSignature Language="C#" Value="public string TaskRootDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.TaskRootDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskRootDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectory : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.TaskRootDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskRootDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-144">取得または計算ノードでジョブの準備タスクのルート ディレクトリを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-144">Gets or sets the root directory of the Job Preparation task on the compute node.</span></span> <span data-ttu-id="d3851-145">このパスを使用すると、ログ ファイルなど、タスクによって作成されたファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3851-145">You can use this path to retrieve files created by the task, such as log files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectoryUrl">
      <MemberSignature Language="C#" Value="public string TaskRootDirectoryUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskRootDirectoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectoryUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskRootDirectoryUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3851-146">取得または計算ノードでジョブの準備タスクのルート ディレクトリに URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3851-146">Gets or sets the URL to the root directory of the Job Preparation task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparationTaskExecutionInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3851-147">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d3851-147">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3851-148">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3851-148">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>