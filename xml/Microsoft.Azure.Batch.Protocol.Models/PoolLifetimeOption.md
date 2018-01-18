<Type Name="PoolLifetimeOption" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption">
  <TypeSignature Language="C#" Value="public enum PoolLifetimeOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PoolLifetimeOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum PoolLifetimeOption" />
  <TypeSignature Language="F#" Value="type PoolLifetimeOption = " />
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
            <span data-ttu-id="19229-101">PoolLifetimeOption の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="19229-101">Defines values for PoolLifetimeOption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Job">
      <MemberSignature Language="C#" Value="Job" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption Job = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.Job" />
      <MemberSignature Language="VB.NET" Value="Job" />
      <MemberSignature Language="F#" Value="Job = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.Job" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="job")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="19229-102">プールは、専用であるジョブの有効期間にわたって存在します。</span><span class="sxs-lookup"><span data-stu-id="19229-102">The pool exists for the lifetime of the job to which it is dedicated.</span></span> <span data-ttu-id="19229-103">バッチ サービスは、ジョブを作成するときに、プールを作成します。</span><span class="sxs-lookup"><span data-stu-id="19229-103">The Batch service creates the pool when it creates the job.</span></span> <span data-ttu-id="19229-104">'ジョブ' オプションをジョブのスケジュールに適用すると、バッチ サービスは、すべてのジョブのスケジュールで作成された新しい自動プールを作成します。</span><span class="sxs-lookup"><span data-stu-id="19229-104">If the 'job' option is applied to a job schedule, the Batch service creates a new auto pool for every job created on the schedule.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="JobSchedule">
      <MemberSignature Language="C#" Value="JobSchedule" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption JobSchedule = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.JobSchedule" />
      <MemberSignature Language="VB.NET" Value="JobSchedule" />
      <MemberSignature Language="F#" Value="JobSchedule = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.JobSchedule" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="jobschedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="19229-105">プールは、ジョブ スケジュールの有効期間にわたって存在します。</span><span class="sxs-lookup"><span data-stu-id="19229-105">The pool exists for the lifetime of the job schedule.</span></span> <span data-ttu-id="19229-106">バッチ サービスは、スケジュールでの最初のジョブを作成するときに、プールを作成します。</span><span class="sxs-lookup"><span data-stu-id="19229-106">The Batch Service creates the pool when it creates the first job on the schedule.</span></span> <span data-ttu-id="19229-107">ジョブではなく、ジョブのスケジュールにのみ、このオプションを適用することがあります。</span><span class="sxs-lookup"><span data-stu-id="19229-107">You may apply this option only to job schedules, not to jobs.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>