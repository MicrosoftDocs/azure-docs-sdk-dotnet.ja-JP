<Type Name="ComputeNodeState" FullName="Microsoft.Azure.Batch.Common.ComputeNodeState">
  <TypeSignature Language="C#" Value="public enum ComputeNodeState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeState" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeState" />
  <TypeSignature Language="F#" Value="type ComputeNodeState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="0f8ef-101">コンピューティング ノードの状態。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-101">The state of a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Creating">
      <MemberSignature Language="C#" Value="Creating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Creating = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Creating" />
      <MemberSignature Language="VB.NET" Value="Creating" />
      <MemberSignature Language="F#" Value="Creating = 5" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Creating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-102">バッチ サービスは、Azure コンピューティングから、基になる仮想マシンを取得が、プールの結合をまだ開始されていません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-102">The Batch service has obtained the underlying virtual machine from Azure Compute, but it has not yet started to join a pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Idle">
      <MemberSignature Language="C#" Value="Idle" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Idle = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />
      <MemberSignature Language="VB.NET" Value="Idle" />
      <MemberSignature Language="F#" Value="Idle = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-103">コンピューティング ノードでは、タスクは現在実行されていません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-103">The compute node is not currently running a task.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LeavingPool">
      <MemberSignature Language="C#" Value="LeavingPool" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState LeavingPool = int32(10)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.LeavingPool" />
      <MemberSignature Language="VB.NET" Value="LeavingPool" />
      <MemberSignature Language="F#" Value="LeavingPool = 10" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.LeavingPool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>10</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-104">コンピューティング ノードがダウンしているため、プール サイズを変更するか、自動スケールまたはユーザーに明示的に削除されるため、プールのままです。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-104">The compute node is leaving the pool, either because the user explicitly removed it or because the pool is resizing or autoscaling down.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="Offline" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Offline = int32(11)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Offline" />
      <MemberSignature Language="VB.NET" Value="Offline" />
      <MemberSignature Language="F#" Value="Offline = 11" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Offline" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>11</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-105">バッチ サービスはコンピューティング ノードで新しいタスクをスケジュールできません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-105">The Batch service will not schedule any new tasks on the compute node.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preempted">
      <MemberSignature Language="C#" Value="Preempted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Preempted = int32(12)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Preempted" />
      <MemberSignature Language="VB.NET" Value="Preempted" />
      <MemberSignature Language="F#" Value="Preempted = 12" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Preempted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>12</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-106">コンピューティング ノードが占有されています。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-106">The compute node has been preempted.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="0f8ef-107">バッチ サービスはコンピューティング ノードで新しいタスクのスケジュールを設定できませんし、プリエンプションの時点で実行されているすべてのタスクがキューに再登録します。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-107">The Batch service will not schedule any new tasks on the compute node and any tasks which were running at the time of preemption were requeued.</span></span>
            <span data-ttu-id="0f8ef-108">バッチ サービスはこの状態にあるノードを回復しようとします。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-108">The Batch service will attempt to recover nodes which are in this state.</span></span> <span data-ttu-id="0f8ef-109">回復後に、時、プリエンプションのノードに存在していたすべてのデータが削除されます。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-109">After recovery, all data that was on the node at the time of the preemption is gone.</span></span>
            </para>
          <para>
            <span data-ttu-id="0f8ef-110">切断されたコンピューティング ノードには課金されません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-110">You are not charged for compute nodes that have been preempted.</span></span>
            </para>
          <para>
            <span data-ttu-id="0f8ef-111">これがノードでのみ発生場所<see cref="P:Microsoft.Azure.Batch.ComputeNode.IsDedicated" />は false。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-111">This can only occurr on nodes where <see cref="P:Microsoft.Azure.Batch.ComputeNode.IsDedicated" /> is false.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Rebooting">
      <MemberSignature Language="C#" Value="Rebooting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Rebooting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Rebooting" />
      <MemberSignature Language="VB.NET" Value="Rebooting" />
      <MemberSignature Language="F#" Value="Rebooting = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Rebooting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-112">コンピューティング ノードを再起動しています。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-112">The compute node is rebooting.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Reimaging">
      <MemberSignature Language="C#" Value="Reimaging" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Reimaging = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Reimaging" />
      <MemberSignature Language="VB.NET" Value="Reimaging" />
      <MemberSignature Language="F#" Value="Reimaging = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Reimaging" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-113">コンピューティング ノードを再適用されています。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-113">The compute node is being reimaged.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Running = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-114">コンピューティング ノードには、(以外の開始タスク) の 1 つまたは複数のタスクで実行されています。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-114">The compute node is running one or more tasks (other than the start task).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Starting">
      <MemberSignature Language="C#" Value="Starting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Starting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Starting" />
      <MemberSignature Language="VB.NET" Value="Starting" />
      <MemberSignature Language="F#" Value="Starting = 6" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Starting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-115">バッチ サービスは基になる仮想マシンで開始しています。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-115">The Batch service is starting on the underlying virtual machine.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StartTaskFailed">
      <MemberSignature Language="C#" Value="StartTaskFailed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState StartTaskFailed = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.StartTaskFailed" />
      <MemberSignature Language="VB.NET" Value="StartTaskFailed" />
      <MemberSignature Language="F#" Value="StartTaskFailed = 8" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.StartTaskFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-116">開始タスクがコンピューティング ノードで失敗しました (および再試行)、waitForSuccess が設定されます。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-116">The start task has failed on the compute node (and exhausted all retries), and waitForSuccess is set.</span></span>  <span data-ttu-id="0f8ef-117">ノードでは、タスクの実行に使用できません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-117">The node is not usable for running tasks.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Unknown = int32(9)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 9" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>9</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-118">バッチ サービスは、計算ノードに接続が切断し、その実際の状態が認識していません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-118">The Batch service has lost contact with the compute node, and does not know its true state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unusable">
      <MemberSignature Language="C#" Value="Unusable" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Unusable = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Unusable" />
      <MemberSignature Language="VB.NET" Value="Unusable" />
      <MemberSignature Language="F#" Value="Unusable = 4" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Unusable" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-119">タスクの実行エラーのためのコンピューティング ノードを使用できません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-119">The compute node cannot be used for task execution due to errors.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitingForStartTask">
      <MemberSignature Language="C#" Value="WaitingForStartTask" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState WaitingForStartTask = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.WaitingForStartTask" />
      <MemberSignature Language="VB.NET" Value="WaitingForStartTask" />
      <MemberSignature Language="F#" Value="WaitingForStartTask = 7" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.WaitingForStartTask" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f8ef-120">コンピューティング ノードで実行されている開始タスクが開始されたが、waitForSuccess が設定されており、開始タスクがまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="0f8ef-120">The start task has started running on the compute node, but waitForSuccess is set and the start task has not yet completed.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>