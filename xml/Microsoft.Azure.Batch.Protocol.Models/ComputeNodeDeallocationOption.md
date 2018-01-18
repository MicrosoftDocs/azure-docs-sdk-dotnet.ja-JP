<Type Name="ComputeNodeDeallocationOption" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeDeallocationOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeDeallocationOption = " />
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
            <span data-ttu-id="2a0a2-101">ComputeNodeDeallocationOption の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-101">Defines values for ComputeNodeDeallocationOption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="requeue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a0a2-102">タスクの実行中のプロセスを終了し、タスクをキューに再登録します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-102">Terminate running task processes and requeue the tasks.</span></span> <span data-ttu-id="2a0a2-103">ノードがあると、タスクが再び実行します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-103">The tasks will run again when a node is available.</span></span> <span data-ttu-id="2a0a2-104">タスクが終了するとすぐにノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-104">Remove nodes as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="retaineddata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a0a2-105">実行中のタスクを完了し、すべてのタスク データ保持期間有効期限が切れるまで待機できるようにします。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-105">Allow currently running tasks to complete, then wait for all task data retention periods to expire.</span></span> <span data-ttu-id="2a0a2-106">待機中に新しいタスクをスケジュールしません。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-106">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="2a0a2-107">すべてのタスク保有期間が終了したとき、ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-107">Remove nodes when all task retention periods have expired.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="taskcompletion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a0a2-108">実行中のタスクを完了できるようにします。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-108">Allow currently running tasks to complete.</span></span> <span data-ttu-id="2a0a2-109">待機中に新しいタスクをスケジュールしません。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-109">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="2a0a2-110">すべてのタスクが完了するとノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-110">Remove nodes when all tasks have completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="terminate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a0a2-111">タスクの実行を終了します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-111">Terminate running tasks.</span></span> <span data-ttu-id="2a0a2-112">終了しましたが再実行されないことを示す failureInfo には、タスクが完了します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-112">The tasks will be completed with failureInfo indicating that they were terminated, and will not run again.</span></span> <span data-ttu-id="2a0a2-113">タスクが終了するとすぐにノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="2a0a2-113">Remove nodes as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>