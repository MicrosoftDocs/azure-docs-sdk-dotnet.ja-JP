<Type Name="JobStatistics" FullName="Microsoft.Azure.Batch.JobStatistics">
  <TypeSignature Language="C#" Value="public class JobStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStatistics" />
  <TypeSignature Language="F#" Value="type JobStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="c1a9d-101">ジョブのリソース使用状況の統計。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-101">Resource usage statistics for the job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedTaskCount">
      <MemberSignature Language="C#" Value="public long FailedTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FailedTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.FailedTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.FailedTaskCount : int64" Usage="Microsoft.Azure.Batch.JobStatistics.FailedTaskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-102">ジョブのタスクの失敗の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-102">Gets the total number of task failures in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KernelCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.KernelCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KernelCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.KernelCpuTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-103">ジョブ内のすべてのタスクで使用された (コア当たり) の合計のカーネル モード CPU 時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-103">Gets the total kernel mode CPU time (per core) consumed by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.JobStatistics.LastUpdateTime" />
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
            <span data-ttu-id="c1a9d-104">これで、統計の最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-104">Gets the time at which the statistics were last updated.</span></span> <span data-ttu-id="c1a9d-105">すべての統計情報は間の範囲に制限されて<see cref="P:Microsoft.Azure.Batch.JobStatistics.StartTime" />とこの値。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-105">All statistics are limited to the range between <see cref="P:Microsoft.Azure.Batch.JobStatistics.StartTime" /> and this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double" Usage="Microsoft.Azure.Batch.JobStatistics.ReadIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-106">ジョブ内のすべてのタスクによってディスクから読み取られた I/O の合計 gibibytes を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-106">Gets the total gibibytes of I/O read from disk by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64" Usage="Microsoft.Azure.Batch.JobStatistics.ReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-107">ディスクが、ジョブ内のすべてのタスクによって実行された読み取り操作の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-107">Gets the total number of disk read operations made by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobStatistics.StartTime" />
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
            <span data-ttu-id="c1a9d-108">統計情報の時間範囲の開始時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-108">Gets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SucceededTaskCount">
      <MemberSignature Language="C#" Value="public long SucceededTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SucceededTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.SucceededTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SucceededTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.SucceededTaskCount : int64" Usage="Microsoft.Azure.Batch.JobStatistics.SucceededTaskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-109">指定された期間中にジョブが正常に完了したタスクの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-109">Gets the total number of tasks successfully completed in the job during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRetryCount">
      <MemberSignature Language="C#" Value="public long TaskRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.TaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRetryCount As Long" />
      <MemberSignature Language="F#" Value="member this.TaskRetryCount : int64" Usage="Microsoft.Azure.Batch.JobStatistics.TaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-110">ジョブのタスクの再試行回数の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-110">Gets the total number of task retries in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.JobStatistics.Url" />
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
            <span data-ttu-id="c1a9d-111">ジョブの統計情報の URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-111">Gets the URL of the job statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.UserCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.UserCpuTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-112">ユーザー モード CPU 時間の合計 (コア当たり)、ジョブ内のすべてのタスクで使用されたを取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-112">Gets the total user mode CPU time (per core) consumed by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.WaitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-113">ジョブのすべてのタスクの合計待機時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-113">Gets the total wait time of all tasks in the job.</span></span> <span data-ttu-id="c1a9d-114">タスクの待機時間は、タスクの作成とタスクの実行の開始までの経過時間として定義されます。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-114">The wait time for a task is defined as the elapsed time between the creation of the task and the start of task execution.</span></span> <span data-ttu-id="c1a9d-115">(失敗したため、タスクが再試行された場合、待機時間は、最新のタスクの実行にかかる時間です。)</span><span class="sxs-lookup"><span data-stu-id="c1a9d-115">(If the task is retried due to failures, the wait time is the time to the most recent task execution.)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c1a9d-116">この値は、アカウントの有効期間の統計情報でのみ報告されます。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-116">This value is only reported in the account lifetime statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobStatistics.WallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-117">経過時間の合計を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-117">Gets the total elapsed time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double" Usage="Microsoft.Azure.Batch.JobStatistics.WriteIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-118">ジョブ内のすべてのタスクによってディスクに書き込まれた I/O の合計 gibibytes を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-118">Gets the total gibibytes of I/O written to disk by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64" Usage="Microsoft.Azure.Batch.JobStatistics.WriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a9d-119">ジョブ内のすべてのタスクによって行われたディスク書き込み操作の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1a9d-119">Gets the total number of disk write operations made by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>