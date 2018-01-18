<Type Name="OnAllTasksComplete" FullName="Microsoft.Azure.Batch.Common.OnAllTasksComplete">
  <TypeSignature Language="C#" Value="public enum OnAllTasksComplete" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OnAllTasksComplete extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.OnAllTasksComplete" />
  <TypeSignature Language="VB.NET" Value="Public Enum OnAllTasksComplete" />
  <TypeSignature Language="F#" Value="type OnAllTasksComplete = " />
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
            <span data-ttu-id="96d65-101">ジョブ内のすべてのタスクが完了した状態で、ときにバッチ サービスが行うアクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="96d65-101">Specifies an action the Batch service should take when all tasks in the job are in the completed state.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NoAction">
      <MemberSignature Language="C#" Value="NoAction" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete NoAction = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OnAllTasksComplete.NoAction" />
      <MemberSignature Language="VB.NET" Value="NoAction" />
      <MemberSignature Language="F#" Value="NoAction = 0" Usage="Microsoft.Azure.Batch.Common.OnAllTasksComplete.NoAction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OnAllTasksComplete</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="96d65-102">何もしません。</span><span class="sxs-lookup"><span data-stu-id="96d65-102">Do nothing.</span></span> <span data-ttu-id="96d65-103">ジョブでは、終了または他のいくつかの方法で無効になっている場合を除きが消えない。</span><span class="sxs-lookup"><span data-stu-id="96d65-103">The job remains active unless terminated or disabled by some other means.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TerminateJob">
      <MemberSignature Language="C#" Value="TerminateJob" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete TerminateJob = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OnAllTasksComplete.TerminateJob" />
      <MemberSignature Language="VB.NET" Value="TerminateJob" />
      <MemberSignature Language="F#" Value="TerminateJob = 1" Usage="Microsoft.Azure.Batch.Common.OnAllTasksComplete.TerminateJob" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OnAllTasksComplete</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="96d65-104">ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="96d65-104">Terminate the job.</span></span> <span data-ttu-id="96d65-105">ジョブの<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />"AllTasksComplete"に設定されています。</span><span class="sxs-lookup"><span data-stu-id="96d65-105">The job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" /> is set to "AllTasksComplete".</span></span> 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>