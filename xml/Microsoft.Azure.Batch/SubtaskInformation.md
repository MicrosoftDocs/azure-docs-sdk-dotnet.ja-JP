<Type Name="SubtaskInformation" FullName="Microsoft.Azure.Batch.SubtaskInformation">
  <TypeSignature Language="C#" Value="public class SubtaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubtaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.SubtaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class SubtaskInformation" />
  <TypeSignature Language="F#" Value="type SubtaskInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="f0966-101">Azure Batch のサブタスクについて説明します。</span><span class="sxs-lookup"><span data-stu-id="f0966-101">Information about an Azure Batch subtask.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ComputeNodeInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeInformation ComputeNodeInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ComputeNodeInformation ComputeNodeInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.ComputeNodeInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeNodeInformation As ComputeNodeInformation" />
      <MemberSignature Language="F#" Value="member this.ComputeNodeInformation : Microsoft.Azure.Batch.ComputeNodeInformation" Usage="Microsoft.Azure.Batch.SubtaskInformation.ComputeNodeInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0966-102">サブタスクが実行したコンピューティング ノードに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-102">Gets the information about the compute node on which the subtask ran.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.SubtaskInformation.ContainerInformation" />
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
            <span data-ttu-id="f0966-103">タスクを実行しているコンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-103">Gets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f0966-104">タスクがコンテナーのコンテキストで実行している場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="f0966-104">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.EndTime" />
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
            <span data-ttu-id="f0966-105">サブタスクが完了した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-105">Gets the time at which the subtask completed.</span></span> <span data-ttu-id="f0966-106">サブタスクがである場合にのみ、このプロパティは設定、<see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Completed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f0966-106">This property is set only if the subtask is in the <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Completed" /> state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.ExitCode" />
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
            <span data-ttu-id="f0966-107">サブタスクのコマンド ラインで指定されたプログラムの終了コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-107">Gets the exit code of the program specified on the subtask command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f0966-108">このプロパティは、サブタスクの場合にのみ返されます、<see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Completed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f0966-108">This property is only returned if the subtask is in the <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Completed" /> state.</span></span> <span data-ttu-id="f0966-109">プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。</span><span class="sxs-lookup"><span data-stu-id="f0966-109">The exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="f0966-110">意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="f0966-110">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="f0966-111">終了コードがコンピューティング ノードなど、オペレーティング システム、プロセスを強制的に終了する場合に生成される可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f0966-111">Note that the exit code may also be generated by the compute node operating system, such as when a process is forcibly terminated.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.SubtaskInformation.FailureInformation" />
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
            <span data-ttu-id="f0966-112">存在する場合、タスクの失敗の記述を情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-112">Gets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Id : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.Id" />
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
            <span data-ttu-id="f0966-113">サブタスクの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-113">Gets the id of the subtask.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.SubtaskState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0966-114">サブタスクの以前の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-114">Gets the previous state of the subtask.</span></span> <span data-ttu-id="f0966-115">サブタスクが、初期の場合、このプロパティを設定しない<see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f0966-115">This property is not set if the subtask is in its initial <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Running" /> state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.PreviousStateTransitionTime" />
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
            <span data-ttu-id="f0966-116">サブタスクが以前の状態を入力する時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-116">Gets the time at which the subtask entered its previous state.</span></span> <span data-ttu-id="f0966-117">サブタスクが、初期の場合、このプロパティを設定しない<see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f0966-117">This property is not set if the subtask is in its initial <see cref="F:Microsoft.Azure.Batch.Common.SubtaskState.Running" /> state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.Result" />
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
            <span data-ttu-id="f0966-118">タスクの実行の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-118">Gets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f0966-119">値が場合<see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />、エラーの詳細は含まれてし、<see cref="P:Microsoft.Azure.Batch.SubtaskInformation.FailureInformation" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="f0966-119">If the value is <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, then the details of the failure can be found in the <see cref="P:Microsoft.Azure.Batch.SubtaskInformation.FailureInformation" /> property.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.StartTime" />
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
            <span data-ttu-id="f0966-120">サブタスクが実行を開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-120">Gets the time at which the subtask started running.</span></span> <span data-ttu-id="f0966-121">サブタスクが再起動した場合は再試行、サブタスクが実行を開始する、最新の時間です。</span><span class="sxs-lookup"><span data-stu-id="f0966-121">If the subtask has been restarted or retried, this is the most recent time at which the subtask started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.SubtaskState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0966-122">サブタスクの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-122">Gets the current state of the subtask.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.SubtaskInformation.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.SubtaskInformation.StateTransitionTime" />
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
            <span data-ttu-id="f0966-123">サブタスクが、現在の状態を入力する時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0966-123">Gets the time at which the subtask entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>