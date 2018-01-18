<Type Name="JobState" FullName="Microsoft.Azure.Batch.Protocol.Models.JobState">
  <TypeSignature Language="C#" Value="public enum JobState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobState" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobState" />
  <TypeSignature Language="F#" Value="type JobState = " />
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
            <span data-ttu-id="eda11-101">JobState の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="eda11-101">Defines values for JobState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.JobState.Active" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="eda11-102">ジョブは、スケジュールされたタスクがある使用可能です。</span><span class="sxs-lookup"><span data-stu-id="eda11-102">The job is available to have tasks scheduled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobState Completed = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 5" Usage="Microsoft.Azure.Batch.Protocol.Models.JobState.Completed" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="eda11-103">すべてのタスクが終了すると、し、システムより多くのタスクまたはジョブにさらなる変更を許可されません。</span><span class="sxs-lookup"><span data-stu-id="eda11-103">All tasks have terminated, and the system will not accept any more tasks or any further changes to the job.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobState Deleting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 6" Usage="Microsoft.Azure.Batch.Protocol.Models.JobState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="deleting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="eda11-104">ユーザーが、ジョブが削除されることを要求されましたが、(たとえば、システムがまだ終了していますのタスクを実行している) ため、削除操作が進行中です。</span><span class="sxs-lookup"><span data-stu-id="eda11-104">A user has requested that the job be deleted, but the delete operation is still in progress (for example, because the system is still terminating running tasks).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobState Disabled = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobState.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.JobState.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="disabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="eda11-105">ユーザーは、ジョブを無効にします。</span><span class="sxs-lookup"><span data-stu-id="eda11-105">A user has disabled the job.</span></span> <span data-ttu-id="eda11-106">タスクが実行されていないと、新しいタスクがスケジュールされません。</span><span class="sxs-lookup"><span data-stu-id="eda11-106">No tasks are running, and no new tasks will be scheduled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabling">
      <MemberSignature Language="C#" Value="Disabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobState Disabling = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobState.Disabling" />
      <MemberSignature Language="VB.NET" Value="Disabling" />
      <MemberSignature Language="F#" Value="Disabling = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.JobState.Disabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="disabling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="eda11-107">ユーザーがジョブを無効にする、要求しますが、無効化操作がまだ進行中 (たとえば、タスクの終了を待機しています)。</span><span class="sxs-lookup"><span data-stu-id="eda11-107">A user has requested that the job be disabled, but the disable operation is still in progress (for example, waiting for tasks to terminate).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Enabling">
      <MemberSignature Language="C#" Value="Enabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobState Enabling = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobState.Enabling" />
      <MemberSignature Language="VB.NET" Value="Enabling" />
      <MemberSignature Language="F#" Value="Enabling = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.JobState.Enabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="enabling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="eda11-108">ユーザーがジョブを有効にする、要求しますが、有効にする操作が進行中です。</span><span class="sxs-lookup"><span data-stu-id="eda11-108">A user has requested that the job be enabled, but the enable operation is still in progress.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminating">
      <MemberSignature Language="C#" Value="Terminating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobState Terminating = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobState.Terminating" />
      <MemberSignature Language="VB.NET" Value="Terminating" />
      <MemberSignature Language="F#" Value="Terminating = 4" Usage="Microsoft.Azure.Batch.Protocol.Models.JobState.Terminating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="terminating")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="eda11-109">ジョブが完了すると、ジョブ マネージャー タスクが完了したか、ユーザーが、ジョブを終了しましたが、(たとえば、ジョブのリリース タスクが実行されている) ために、終了操作が進行中です。</span><span class="sxs-lookup"><span data-stu-id="eda11-109">The job is about to complete, either because a Job Manager task has completed or because the user has terminated the job, but the terminate operation is still in progress (for example, because Job Release tasks are running).</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>