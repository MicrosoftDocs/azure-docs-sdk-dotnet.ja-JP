<Type Name="ComputeNodeState" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState">
  <TypeSignature Language="C#" Value="public enum ComputeNodeState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState" />
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
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="58458-101">ComputeNodeState の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="58458-101">Defines values for ComputeNodeState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Creating">
      <MemberSignature Language="C#" Value="Creating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Creating = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Creating" />
      <MemberSignature Language="VB.NET" Value="Creating" />
      <MemberSignature Language="F#" Value="Creating = 5" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Creating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="creating")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-102">バッチ サービスは、Azure コンピューティングから、基になる仮想マシンを取得が、プールの結合をまだ開始されていません。</span><span class="sxs-lookup"><span data-stu-id="58458-102">The Batch service has obtained the underlying virtual machine from Azure Compute, but it has not yet started to join the pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Idle">
      <MemberSignature Language="C#" Value="Idle" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Idle = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Idle" />
      <MemberSignature Language="VB.NET" Value="Idle" />
      <MemberSignature Language="F#" Value="Idle = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Idle" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="idle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-103">ノードでは、タスクは現在実行されていません。</span><span class="sxs-lookup"><span data-stu-id="58458-103">The node is not currently running a task.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LeavingPool">
      <MemberSignature Language="C#" Value="LeavingPool" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState LeavingPool = int32(10)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.LeavingPool" />
      <MemberSignature Language="VB.NET" Value="LeavingPool" />
      <MemberSignature Language="F#" Value="LeavingPool = 10" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.LeavingPool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="leavingpool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>10</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-104">ノードがダウンしているため、プール サイズを変更するか、自動スケールまたはユーザーに明示的に削除されるため、プールのままです。</span><span class="sxs-lookup"><span data-stu-id="58458-104">The node is leaving the pool, either because the user explicitly removed it or because the pool is resizing or autoscaling down.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="Offline" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Offline = int32(11)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Offline" />
      <MemberSignature Language="VB.NET" Value="Offline" />
      <MemberSignature Language="F#" Value="Offline = 11" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Offline" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="offline")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>11</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-105">ノードが現在実行されていないタスク、およびノードに新しいタスクのスケジュールが無効になっています。</span><span class="sxs-lookup"><span data-stu-id="58458-105">The node is not currently running a task, and scheduling of new tasks to the node is disabled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preempted">
      <MemberSignature Language="C#" Value="Preempted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Preempted = int32(12)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Preempted" />
      <MemberSignature Language="VB.NET" Value="Preempted" />
      <MemberSignature Language="F#" Value="Preempted = 12" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Preempted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="preempted")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>12</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-106">優先度の低いノードが占有されています。</span><span class="sxs-lookup"><span data-stu-id="58458-106">The low-priority node has been preempted.</span></span> <span data-ttu-id="58458-107">別のノードが利用可能になったら、切り替えだった場合、ノード上で実行されているタスクを再スケジュールされます。</span><span class="sxs-lookup"><span data-stu-id="58458-107">Tasks which were running on the node when it was pre-empted will be rescheduled when another node becomes available.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Rebooting">
      <MemberSignature Language="C#" Value="Rebooting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Rebooting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Rebooting" />
      <MemberSignature Language="VB.NET" Value="Rebooting" />
      <MemberSignature Language="F#" Value="Rebooting = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Rebooting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="rebooting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-108">ノードを再起動しています。</span><span class="sxs-lookup"><span data-stu-id="58458-108">The node is rebooting.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Reimaging">
      <MemberSignature Language="C#" Value="Reimaging" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Reimaging = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Reimaging" />
      <MemberSignature Language="VB.NET" Value="Reimaging" />
      <MemberSignature Language="F#" Value="Reimaging = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Reimaging" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="reimaging")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-109">ノードが再イメージ化します。</span><span class="sxs-lookup"><span data-stu-id="58458-109">The node is reimaging.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Running = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="running")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-110">ノードは (以外の開始タスク) の 1 つまたは複数のタスクを実行しています。</span><span class="sxs-lookup"><span data-stu-id="58458-110">The node is running one or more tasks (other than a start task).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Starting">
      <MemberSignature Language="C#" Value="Starting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Starting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Starting" />
      <MemberSignature Language="VB.NET" Value="Starting" />
      <MemberSignature Language="F#" Value="Starting = 6" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Starting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="starting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-111">バッチ サービスは基になる仮想マシンで開始しています。</span><span class="sxs-lookup"><span data-stu-id="58458-111">The Batch service is starting on the underlying virtual machine.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StartTaskFailed">
      <MemberSignature Language="C#" Value="StartTaskFailed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState StartTaskFailed = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.StartTaskFailed" />
      <MemberSignature Language="VB.NET" Value="StartTaskFailed" />
      <MemberSignature Language="F#" Value="StartTaskFailed = 8" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.StartTaskFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="starttaskfailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-112">開始タスクがコンピューティング ノードで失敗しました (および再試行)、waitForSuccess が設定されます。</span><span class="sxs-lookup"><span data-stu-id="58458-112">The start task has failed on the compute node (and exhausted all retries), and waitForSuccess is set.</span></span> <span data-ttu-id="58458-113">ノードでは、タスクの実行に使用できません。</span><span class="sxs-lookup"><span data-stu-id="58458-113">The node is not usable for running tasks.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Unknown = int32(9)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 9" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="unknown")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>9</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-114">バッチ サービスは、ノードとの接続が切断し、その実際の状態が認識していません。</span><span class="sxs-lookup"><span data-stu-id="58458-114">The Batch service has lost contact with the node, and does not know its true state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unusable">
      <MemberSignature Language="C#" Value="Unusable" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState Unusable = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Unusable" />
      <MemberSignature Language="VB.NET" Value="Unusable" />
      <MemberSignature Language="F#" Value="Unusable = 4" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.Unusable" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="unusable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-115">ノードは、エラーのためのタスクの実行に使用できません。</span><span class="sxs-lookup"><span data-stu-id="58458-115">The node cannot be used for task execution due to errors.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitingForStartTask">
      <MemberSignature Language="C#" Value="WaitingForStartTask" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState WaitingForStartTask = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.WaitingForStartTask" />
      <MemberSignature Language="VB.NET" Value="WaitingForStartTask" />
      <MemberSignature Language="F#" Value="WaitingForStartTask = 7" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState.WaitingForStartTask" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="waitingForStartTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="58458-116">コンピューティング ノードで実行されている開始タスクが開始されたが、waitForSuccess が設定されており、開始タスクがまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="58458-116">The start task has started running on the compute node, but waitForSuccess is set and the start task has not yet completed.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>