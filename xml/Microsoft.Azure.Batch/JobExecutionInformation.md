<Type Name="JobExecutionInformation" FullName="Microsoft.Azure.Batch.JobExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="c1a45-101">Azure Batch のジョブの実行に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="c1a45-101">Information about the execution of an Azure Batch job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.JobExecutionInformation.EndTime" />
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
            <span data-ttu-id="c1a45-102">このジョブの完了時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a45-102">Gets the completion time of this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobExecutionInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string" Usage="Microsoft.Azure.Batch.JobExecutionInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a45-103">このジョブの Id のプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a45-103">Gets the pool Id of this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobSchedulingError SchedulingError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobSchedulingError SchedulingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobExecutionInformation.SchedulingError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SchedulingError As JobSchedulingError" />
      <MemberSignature Language="F#" Value="member this.SchedulingError : Microsoft.Azure.Batch.JobSchedulingError" Usage="Microsoft.Azure.Batch.JobExecutionInformation.SchedulingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobSchedulingError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a45-104">ジョブのスケジュール設定、バッチ サービスで発生したエラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a45-104">Gets the error encountered by the Batch service in scheduling the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobExecutionInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a45-105">ジョブの作成時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a45-105">Gets the creation time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateReason">
      <MemberSignature Language="C#" Value="public string TerminateReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TerminateReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TerminateReason As String" />
      <MemberSignature Language="F#" Value="member this.TerminateReason : string" Usage="Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a45-106">ジョブが完了した状態に移行する理由を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a45-106">Gets the reason for job moving to completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>