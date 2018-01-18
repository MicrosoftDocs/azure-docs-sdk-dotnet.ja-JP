<Type Name="ComputeNodeRebootOption" FullName="Microsoft.Azure.Batch.Common.ComputeNodeRebootOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeRebootOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeRebootOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeRebootOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeRebootOption = " />
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
            <span data-ttu-id="bd8f8-101">コンピューティング ノードを再起動するタイミングと、実行中のタスクの処理方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-101">Specifies when to reboot a compute node and what to do with currently running tasks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeRebootOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd8f8-102">タスクの実行を終了し、そのキューに再登録します。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-102">Terminate running tasks and requeue them.</span></span> <span data-ttu-id="bd8f8-103">このタスクは、ジョブが有効になると再び実行されます。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-103">The tasks will run again when the job is enabled.</span></span> <span data-ttu-id="bd8f8-104">タスクが終了したらすぐに、コンピューティング ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-104">Restart the compute node as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeRebootOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd8f8-105">実行中のタスクを完了し、すべてのタスク データ保持期間有効期限が切れるまで待機できるようにします。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-105">Allow currently running tasks to complete, then wait for all task data retention periods to expire.</span></span> <span data-ttu-id="bd8f8-106">待機中に新しいタスクをスケジュールしません。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-106">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="bd8f8-107">すべてのタスクの保有期間の期限が切れている場合は、コンピューティング ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-107">Restart the compute node when all task retention periods have expired.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeRebootOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd8f8-108">実行中のタスクを完了できるようにします。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-108">Allow currently running tasks to complete.</span></span> <span data-ttu-id="bd8f8-109">待機中に新しいタスクをスケジュールしません。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-109">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="bd8f8-110">すべてのタスクが完了したときに、コンピューティング ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-110">Restart the compute node when all tasks have completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeRebootOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd8f8-111">タスクの実行を終了します。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-111">Terminate running tasks.</span></span> <span data-ttu-id="bd8f8-112">タスクは再び実行されることがありません。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-112">The tasks will not run again.</span></span> <span data-ttu-id="bd8f8-113">タスクが終了したらすぐに、コンピューティング ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="bd8f8-113">Restart the compute node as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>