<Type Name="JobScheduleStatistics" FullName="Microsoft.Azure.Batch.JobScheduleStatistics">
  <TypeSignature Language="C#" Value="public class JobScheduleStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobScheduleStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleStatistics" />
  <TypeSignature Language="F#" Value="type JobScheduleStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="a2c6d-101">リソース使用量の統計、<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-101">Resource usage statistics for a <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedTaskCount">
      <MemberSignature Language="C#" Value="public long FailedTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FailedTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.FailedTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.FailedTaskCount : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.FailedTaskCount" />
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
            <span data-ttu-id="a2c6d-102">指定された期間中に失敗したジョブのタスクの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-102">Gets the total number of tasks in the job that failed during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KernelCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.KernelCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KernelCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.KernelCpuTime" />
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
            <span data-ttu-id="a2c6d-103">ジョブのスケジュールですべてのタスクで使用された (コア当たり) の合計のカーネル モード CPU 時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-103">Gets the total kernel mode CPU time (per core) consumed by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.LastUpdateTime" />
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
            <span data-ttu-id="a2c6d-104">これで、統計の最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-104">Gets the time at which the statistics were last updated.</span></span> <span data-ttu-id="a2c6d-105">すべての統計情報は間の範囲に制限されて<see cref="P:Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" />とこの値。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-105">All statistics are limited to the range between <see cref="P:Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" /> and this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOGiB" />
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
            <span data-ttu-id="a2c6d-106">ジョブのスケジュール内のすべてのタスクによってディスクから読み取られた I/O の合計 gibibytes を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-106">Gets the total gibibytes of I/O read from disk by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOps" />
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
            <span data-ttu-id="a2c6d-107">ジョブのスケジュール内のすべてのタスクによって実行された読み取り操作のディスクの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-107">Gets the total number of disk read operations made by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" />
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
            <span data-ttu-id="a2c6d-108">統計情報の時間範囲の開始時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-108">Gets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SucceededTaskCount">
      <MemberSignature Language="C#" Value="public long SucceededTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SucceededTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.SucceededTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SucceededTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.SucceededTaskCount : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.SucceededTaskCount" />
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
            <span data-ttu-id="a2c6d-109">ジョブのスケジュールで正常に完了したタスクの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-109">Gets the total number of tasks successfully completed in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRetryCount">
      <MemberSignature Language="C#" Value="public long TaskRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.TaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRetryCount As Long" />
      <MemberSignature Language="F#" Value="member this.TaskRetryCount : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.TaskRetryCount" />
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
            <span data-ttu-id="a2c6d-110">ジョブのスケジュール内のすべてのタスクで発生した再試行の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-110">Gets the total number of retries that occurred on all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.Url" />
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
            <span data-ttu-id="a2c6d-111">統計情報の URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-111">Gets the URL of the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.UserCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.UserCpuTime" />
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
            <span data-ttu-id="a2c6d-112">ユーザー モード CPU 時間の合計 (コア当たり) ジョブのスケジュール内のすべてのタスクで使用されるを取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-112">Gets the total user mode CPU time (per core) consumed by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WaitTime" />
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
            <span data-ttu-id="a2c6d-113">スケジュールの下に作成されたジョブのすべてのタスクの合計待機時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-113">Gets the total wait time of all tasks in jobs created under the schedule.</span></span> <span data-ttu-id="a2c6d-114">タスクの待機時間は、タスクの作成とタスクの実行の開始までの経過時間として定義されます。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-114">The wait time for a task is defined as the elapsed time between the creation of the task and the start of task execution.</span></span> <span data-ttu-id="a2c6d-115">(失敗したため、タスクが再試行された場合、待機時間は、最新のタスクの実行にかかる時間です。)</span><span class="sxs-lookup"><span data-stu-id="a2c6d-115">(If the task is retried due to failures, the wait time is the time to the most recent task execution.)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a2c6d-116">この値は、アカウントの有効期間の統計情報でのみ報告されます。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-116">This value is only reported in the account lifetime statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WallClockTime" />
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
            <span data-ttu-id="a2c6d-117">ジョブのスケジュール内のすべてのタスクの合計のウォール クロック時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-117">Gets the total wall clock time of all tasks in the job schedule.</span></span> <span data-ttu-id="a2c6d-118">いずれかのタスクが複数回再試行された場合は、これに含まれているすべてのタスク再試行のウォール クロック時間に注意してください。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-118">Note that if any task was retried multiple times, this includes the wall clock time of all the task retries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOGiB" />
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
            <span data-ttu-id="a2c6d-119">ジョブのスケジュール内のすべてのタスクによってディスクに書き込まれる I/O の合計 gibibytes を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-119">Gets the total gibibytes of I/O written to disk by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOps" />
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
            <span data-ttu-id="a2c6d-120">ジョブのスケジュール内のすべてのタスクで行われたディスク書き込み操作の合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2c6d-120">Gets the total number of disk write operations made by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>