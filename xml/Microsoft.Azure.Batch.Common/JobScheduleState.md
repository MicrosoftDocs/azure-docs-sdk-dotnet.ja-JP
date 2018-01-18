<Type Name="JobScheduleState" FullName="Microsoft.Azure.Batch.Common.JobScheduleState">
  <TypeSignature Language="C#" Value="public enum JobScheduleState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobScheduleState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.JobScheduleState" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobScheduleState" />
  <TypeSignature Language="F#" Value="type JobScheduleState = " />
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
            <span data-ttu-id="12a5d-101">ジョブ スケジュールの状態。</span><span class="sxs-lookup"><span data-stu-id="12a5d-101">The state of a job schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="12a5d-102">ジョブのスケジュールがアクティブであり、スケジュールに従ってジョブが作成されます。</span><span class="sxs-lookup"><span data-stu-id="12a5d-102">The job schedule is active and will create jobs as per its schedule.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Completed = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 1" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="12a5d-103">終了時刻に到達するか、明示的に終了しているユーザーをスケジュールが終了しました。</span><span class="sxs-lookup"><span data-stu-id="12a5d-103">The schedule has terminated, either by reaching its end time or by the user terminating it explicitly.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Deleting = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 4" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="12a5d-104">ユーザーが、スケジュールが削除されることを要求されましたが、削除操作が進行中です。</span><span class="sxs-lookup"><span data-stu-id="12a5d-104">The user has requested that the schedule be deleted, but the delete operation is still in progress.</span></span> <span data-ttu-id="12a5d-105">スケジューラがこのスケジュールの新しいジョブを開始しませんが、既存のアクティブなジョブを実行し続けます。</span><span class="sxs-lookup"><span data-stu-id="12a5d-105">The scheduler will not initiate any new jobs for this schedule, but any existing active job will continue to run.</span></span> <span data-ttu-id="12a5d-106">既存のジョブが完了すると、スケジュールが削除されます。</span><span class="sxs-lookup"><span data-stu-id="12a5d-106">The schedule will be deleted when the existing job completes.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Disabled = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 2" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="12a5d-107">ユーザーは、スケジュールを無効にします。</span><span class="sxs-lookup"><span data-stu-id="12a5d-107">The user has disabled the schedule.</span></span> <span data-ttu-id="12a5d-108">スケジューラは、このスケジュールで、新しいジョブは開始されませんが、既存のアクティブなジョブを実行し続けます。</span><span class="sxs-lookup"><span data-stu-id="12a5d-108">The scheduler will not initiate any new jobs will on this schedule, but any existing active job will continue to run.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminating">
      <MemberSignature Language="C#" Value="Terminating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Terminating = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />
      <MemberSignature Language="VB.NET" Value="Terminating" />
      <MemberSignature Language="F#" Value="Terminating = 3" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="12a5d-109">スケジュールが他の作業を行うには明示的に設定されているか、ユーザーによる中断しますが、終了操作が進行中です。</span><span class="sxs-lookup"><span data-stu-id="12a5d-109">The schedule has no more work to do, or has been explicitly terminated by the user, but the termination operation is still in progress.</span></span> <span data-ttu-id="12a5d-110">スケジューラがこのスケジュールの新しいジョブを開始しませんも、既存のジョブのアクティブです。</span><span class="sxs-lookup"><span data-stu-id="12a5d-110">The scheduler will not initiate any new jobs for this schedule, nor is any existing job active.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>