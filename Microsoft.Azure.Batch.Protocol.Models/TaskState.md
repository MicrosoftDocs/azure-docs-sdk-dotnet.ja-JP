<Type Name="TaskState" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskState">
  <TypeSignature Language="C#" Value="public enum TaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskState" />
  <TypeSignature Language="VB.NET" Value="Public Enum TaskState" />
  <TypeSignature Language="F#" Value="type TaskState = " />
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
            <span data-ttu-id="73668-101">TaskState の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="73668-101">Defines values for TaskState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="active")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="73668-102">タスクは、キューに置かれたできの実行は、コンピューティング ノードに現在割り当てられていません。</span><span class="sxs-lookup"><span data-stu-id="73668-102">The task is queued and able to run, but is not currently assigned to a compute node.</span></span> <span data-ttu-id="73668-103">タスクをこの状態に無効になっている後に有効になっているときに、作成時または失敗した実行後に再試行を待機しているときにします。</span><span class="sxs-lookup"><span data-stu-id="73668-103">A task enters this state when it is created, when it is enabled after being disabled, or when it is awaiting a retry after a failed run.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="completed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="73668-104">タスクが実行するには通常、タスクが正常に完了したか、タスクが正常に完了し、再試行の制限が不足ため対象ではなくなりました。</span><span class="sxs-lookup"><span data-stu-id="73668-104">The task is no longer eligible to run, usually because the task has finished successfully, or the task has finished unsuccessfully and has exhausted its retry limit.</span></span> <span data-ttu-id="73668-105">タスクは、完了した場合は、タスクの起動時にエラーが発生した場合や、タスクが終了された場合にもマークされます。</span><span class="sxs-lookup"><span data-stu-id="73668-105">A task is also marked as completed if an error occurred launching the task, or when the task has been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preparing">
      <MemberSignature Language="C#" Value="Preparing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Preparing = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Preparing" />
      <MemberSignature Language="VB.NET" Value="Preparing" />
      <MemberSignature Language="F#" Value="Preparing = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Preparing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="preparing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="73668-106">タスクは、コンピューティング ノードに割り当てられているが、ノード、完了に必要なジョブの準備タスクが待機しています。</span><span class="sxs-lookup"><span data-stu-id="73668-106">The task has been assigned to a compute node, but is waiting for a required Job Preparation task to complete on the node.</span></span> <span data-ttu-id="73668-107">ジョブの準備タスクが成功した場合、タスクが実行中に移動します。</span><span class="sxs-lookup"><span data-stu-id="73668-107">If the Job Preparation task succeeds, the task will move to running.</span></span> <span data-ttu-id="73668-108">ジョブの準備タスクが失敗した場合、タスクはアクティブに戻り、別のノードに割り当てられるに対象となります。</span><span class="sxs-lookup"><span data-stu-id="73668-108">If the Job Preparation task fails, the task will return to active and will be eligible to be assigned to a different node.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Running = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Running" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="73668-109">タスクが、コンピューティング ノードで実行します。</span><span class="sxs-lookup"><span data-stu-id="73668-109">The task is running on a compute node.</span></span> <span data-ttu-id="73668-110">これには、リソース ファイルをダウンロードしたり、タスクで指定されたアプリケーション パッケージの配置などのタスク レベルの準備が含まれます - ことが必ずしもタスクのコマンドラインの実行が開始されたことです。</span><span class="sxs-lookup"><span data-stu-id="73668-110">This includes task-level preparation such as downloading resource files or deploying application packages specified on the task - it does not necessarily mean that the task command line has started executing.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>