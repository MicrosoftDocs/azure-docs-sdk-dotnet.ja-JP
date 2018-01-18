<Type Name="StartTaskInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation">
  <TypeSignature Language="C#" Value="public class StartTaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTaskInformation" />
  <TypeSignature Language="F#" Value="type StartTaskInformation = class" />
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
            <span data-ttu-id="24059-101">コンピューティング ノードで実行されている開始タスクに関する情報。</span><span class="sxs-lookup"><span data-stu-id="24059-101">Information about a start task running on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTaskInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.#ctor" />
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
            <span data-ttu-id="24059-102">StartTaskInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24059-102">Initializes a new instance of the StartTaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTaskInformation (Microsoft.Azure.Batch.Protocol.Models.StartTaskState state, DateTime startTime, int retryCount, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;DateTime&gt; lastRetryTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.StartTaskState state, valuetype System.DateTime startTime, int32 retryCount, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRetryTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.#ctor(Microsoft.Azure.Batch.Protocol.Models.StartTaskState,System.DateTime,System.Int32,System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As StartTaskState, startTime As DateTime, retryCount As Integer, Optional endTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional lastRetryTime As Nullable(Of DateTime) = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation : Microsoft.Azure.Batch.Protocol.Models.StartTaskState * DateTime * int * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation (state, startTime, retryCount, endTime, exitCode, containerInfo, failureInfo, lastRetryTime, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Batch.Protocol.Models.StartTaskState" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="retryCount" Type="System.Int32" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="lastRetryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="24059-103">コンピューティング ノードで、開始タスクの状態。</span><span class="sxs-lookup"><span data-stu-id="24059-103">The state of the start task on the compute node.</span></span></param>
        <param name="startTime"><span data-ttu-id="24059-104">開始タスクが実行を開始された時刻。</span><span class="sxs-lookup"><span data-stu-id="24059-104">The time at which the start task started running.</span></span></param>
        <param name="retryCount"><span data-ttu-id="24059-105">Batch サービスによりタスクが再試行された回数。</span><span class="sxs-lookup"><span data-stu-id="24059-105">The number of times the task has been retried by the Batch service.</span></span></param>
        <param name="endTime"><span data-ttu-id="24059-106">開始タスクが実行を停止した時刻。</span><span class="sxs-lookup"><span data-stu-id="24059-106">The time at which the start task stopped running.</span></span></param>
        <param name="exitCode"><span data-ttu-id="24059-107">開始タスクのコマンドラインで指定されたプログラムの終了コード。</span><span class="sxs-lookup"><span data-stu-id="24059-107">The exit code of the program specified on the start task command line.</span></span></param>
        <param name="containerInfo"><span data-ttu-id="24059-108">タスクを実行しているコンテナーについて説明します。</span><span class="sxs-lookup"><span data-stu-id="24059-108">Information about the container under which the task is executing.</span></span></param>
        <param name="failureInfo"><span data-ttu-id="24059-109">存在する場合、タスクの失敗を説明する情報です。</span><span class="sxs-lookup"><span data-stu-id="24059-109">Information describing the task failure, if any.</span></span></param>
        <param name="lastRetryTime"><span data-ttu-id="24059-110">タスクの再試行が実行を開始する最新の時間。</span><span class="sxs-lookup"><span data-stu-id="24059-110">The most recent time at which a retry of the task started running.</span></span></param>
        <param name="result"><span data-ttu-id="24059-111">タスクの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="24059-111">The result of the task execution.</span></span></param>
        <summary>
            <span data-ttu-id="24059-112">StartTaskInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24059-112">Initializes a new instance of the StartTaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ContainerInfo" />
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
            <span data-ttu-id="24059-113">取得またはタスクを実行しているコンテナーに関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-113">Gets or sets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-114">タスクがコンテナーのコンテキストで実行している場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="24059-114">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.EndTime" />
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
            <span data-ttu-id="24059-115">取得または開始タスクが実行を停止した時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-115">Gets or sets the time at which the start task stopped running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-116">これは、最新の終了時刻に実行、開始タスク (場合でも障害を実行し、再試行が保留中) 実行が完了した場合です。</span><span class="sxs-lookup"><span data-stu-id="24059-116">This is the end time of the most recent run of the start task, if that run has completed (even if that run failed and a retry is pending).</span></span> <span data-ttu-id="24059-117">この要素は、開始タスクが現在実行されている場合は、現在ではありません。</span><span class="sxs-lookup"><span data-stu-id="24059-117">This element is not present if the start task is currently running.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ExitCode" />
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
            <span data-ttu-id="24059-118">取得または開始タスクのコマンドラインで指定されたプログラムの終了コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-118">Gets or sets the exit code of the program specified on the start task command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-119">このプロパティは、開始タスクが完了した状態で場合にのみに設定されます。</span><span class="sxs-lookup"><span data-stu-id="24059-119">This property is set only if the start task is in the completed state.</span></span> <span data-ttu-id="24059-120">一般に、プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。</span><span class="sxs-lookup"><span data-stu-id="24059-120">In general, the exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="24059-121">意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="24059-121">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="24059-122">ただし、バッチ サービスには (タイムアウト、または API を使用してユーザーの終了) のため、開始タスクが終了した場合、オペレーティング システム定義の終了コードを参照してください可能性があります。</span><span class="sxs-lookup"><span data-stu-id="24059-122">However, if the Batch service terminates the start task (due to timeout, or user termination via the API) you may see an operating system-defined exit code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.FailureInfo" />
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
            <span data-ttu-id="24059-123">取得または存在する場合に、タスクの失敗を示す情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-123">Gets or sets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-124">このプロパティは、タスクが完了した状態の場合にのみ設定され、エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="24059-124">This property is set only if the task is in the completed state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.LastRetryTime" />
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
            <span data-ttu-id="24059-125">取得またはタスクの再試行が実行を開始する最新の時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-125">Gets or sets the most recent time at which a retry of the task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-126">この要素は、タスクが再試行された場合にのみ存在 (つまり retryCount が 0 以外)。</span><span class="sxs-lookup"><span data-stu-id="24059-126">This element is present only if the task was retried (i.e. retryCount is nonzero).</span></span> <span data-ttu-id="24059-127">存在する場合、これは通常、開始時刻と同じですが再試行; 以外の理由により、タスクが再起動された場合は異なる場合があります。たとえば、再試行中にコンピューティング ノードを再起動すると場合、startTime が更新されますが、lastRetryTime はありません。</span><span class="sxs-lookup"><span data-stu-id="24059-127">If present, this is typically the same as startTime, but may be different if the task has been restarted for reasons other than retry; for example, if the compute node was rebooted during a retry, then the startTime is updated but the lastRetryTime is not.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.Result" />
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
            <span data-ttu-id="24059-128">取得またはタスクの実行の結果を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-128">Gets or sets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-129">場合は、値は '失敗'、エラーの詳細は failureInfo プロパティで確認できます。</span><span class="sxs-lookup"><span data-stu-id="24059-129">If the value is 'failed', then the details of the failure can be found in the failureInfo property.</span></span> <span data-ttu-id="24059-130">使用可能な値が含まれます: 'は success'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="24059-130">Possible values include: 'success', 'failure'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.RetryCount" />
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
            <span data-ttu-id="24059-131">取得またはタスクが、Batch service によって再試行された回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-131">Gets or sets the number of times the task has been retried by the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-132">タスクのアプリケーション エラー (0 以外の終了コード) は再試行処理前のエラー (タスクを実行できませんでした) され、ファイルのアップロード エラーは再試行されません。</span><span class="sxs-lookup"><span data-stu-id="24059-132">Task application failures (non-zero exit code) are retried, pre-processing errors (the task could not be run) and file upload errors are not retried.</span></span> <span data-ttu-id="24059-133">バッチ サービスは、制約で指定された上限に達するまでタスクを再試行します。</span><span class="sxs-lookup"><span data-stu-id="24059-133">The Batch service will retry the task up to the limit specified by the constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.StartTime" />
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
            <span data-ttu-id="24059-134">取得または開始タスクが実行を開始された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-134">Gets or sets the time at which the start task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-135">タスクを再起動するか、または再試行するたびにこの値はリセット (つまり、これは、最も最近使用した、開始タスクの開始時刻を実行している)。</span><span class="sxs-lookup"><span data-stu-id="24059-135">This value is reset every time the task is restarted or retried (that is, this is the most recent time at which the start task started running).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTaskState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.StartTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As StartTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Protocol.Models.StartTaskState with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.State" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24059-136">取得または計算ノードで、開始タスクの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="24059-136">Gets or sets the state of the start task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="24059-137">使用可能な値が含まれます: 'を実行している'、'完了'</span><span class="sxs-lookup"><span data-stu-id="24059-137">Possible values include: 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="startTaskInformation.Validate " />
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
            <span data-ttu-id="24059-138">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="24059-138">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="24059-139">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="24059-139">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>