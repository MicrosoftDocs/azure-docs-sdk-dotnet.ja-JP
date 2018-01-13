<Type Name="JobStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.JobStatistics">
  <TypeSignature Language="C#" Value="public class JobStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStatistics" />
  <TypeSignature Language="F#" Value="type JobStatistics = class" />
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
            <span data-ttu-id="fd127-101">ジョブのリソース使用状況の統計。</span><span class="sxs-lookup"><span data-stu-id="fd127-101">Resource usage statistics for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fd127-102">JobStatistics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fd127-102">Initializes a new instance of the JobStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatistics (string url, DateTime startTime, DateTime lastUpdateTime, TimeSpan userCPUTime, TimeSpan kernelCPUTime, TimeSpan wallClockTime, long readIOps, long writeIOps, double readIOGiB, double writeIOGiB, long numSucceededTasks, long numFailedTasks, long numTaskRetries, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, valuetype System.TimeSpan userCPUTime, valuetype System.TimeSpan kernelCPUTime, valuetype System.TimeSpan wallClockTime, int64 readIOps, int64 writeIOps, float64 readIOGiB, float64 writeIOGiB, int64 numSucceededTasks, int64 numFailedTasks, int64 numTaskRetries, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.#ctor(System.String,System.DateTime,System.DateTime,System.TimeSpan,System.TimeSpan,System.TimeSpan,System.Int64,System.Int64,System.Double,System.Double,System.Int64,System.Int64,System.Int64,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, startTime As DateTime, lastUpdateTime As DateTime, userCPUTime As TimeSpan, kernelCPUTime As TimeSpan, wallClockTime As TimeSpan, readIOps As Long, writeIOps As Long, readIOGiB As Double, writeIOGiB As Double, numSucceededTasks As Long, numFailedTasks As Long, numTaskRetries As Long, waitTime As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobStatistics : string * DateTime * DateTime * TimeSpan * TimeSpan * TimeSpan * int64 * int64 * double * double * int64 * int64 * int64 * TimeSpan -&gt; Microsoft.Azure.Batch.Protocol.Models.JobStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobStatistics (url, startTime, lastUpdateTime, userCPUTime, kernelCPUTime, wallClockTime, readIOps, writeIOps, readIOGiB, writeIOGiB, numSucceededTasks, numFailedTasks, numTaskRetries, waitTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="userCPUTime" Type="System.TimeSpan" />
        <Parameter Name="kernelCPUTime" Type="System.TimeSpan" />
        <Parameter Name="wallClockTime" Type="System.TimeSpan" />
        <Parameter Name="readIOps" Type="System.Int64" />
        <Parameter Name="writeIOps" Type="System.Int64" />
        <Parameter Name="readIOGiB" Type="System.Double" />
        <Parameter Name="writeIOGiB" Type="System.Double" />
        <Parameter Name="numSucceededTasks" Type="System.Int64" />
        <Parameter Name="numFailedTasks" Type="System.Int64" />
        <Parameter Name="numTaskRetries" Type="System.Int64" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="fd127-103">統計情報の URL です。</span><span class="sxs-lookup"><span data-stu-id="fd127-103">The URL of the statistics.</span></span></param>
        <param name="startTime"><span data-ttu-id="fd127-104">統計情報の時間範囲の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="fd127-104">The start time of the time range covered by the statistics.</span></span></param>
        <param name="lastUpdateTime"><span data-ttu-id="fd127-105">これで、統計の最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="fd127-105">The time at which the statistics were last updated.</span></span> <span data-ttu-id="fd127-106">すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。</span><span class="sxs-lookup"><span data-stu-id="fd127-106">All statistics are limited to the range between startTime and lastUpdateTime.</span></span></param>
        <param name="userCPUTime"><span data-ttu-id="fd127-107">ユーザー モード CPU 時間の合計 (すべてのコアとすべてのコンピューティング ノード間で合計)、ジョブ内のすべてのタスクで使用します。</span><span class="sxs-lookup"><span data-stu-id="fd127-107">The total user mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span></param>
        <param name="kernelCPUTime"><span data-ttu-id="fd127-108">カーネル モード CPU 時間の合計 (すべてのコアとすべてのコンピューティング ノード間で合計)、ジョブ内のすべてのタスクで使用します。</span><span class="sxs-lookup"><span data-stu-id="fd127-108">The total kernel mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span></param>
        <param name="wallClockTime"><span data-ttu-id="fd127-109">ジョブ内のすべてのタスクの合計のウォール クロック時間。</span><span class="sxs-lookup"><span data-stu-id="fd127-109">The total wall clock time of all tasks in the job.</span></span></param>
        <param name="readIOps"><span data-ttu-id="fd127-110">ディスクの合計数は、ジョブ内のすべてのタスクで行われる操作を読み取る。</span><span class="sxs-lookup"><span data-stu-id="fd127-110">The total number of disk read operations made by all tasks in the job.</span></span></param>
        <param name="writeIOps"><span data-ttu-id="fd127-111">ディスクの合計数は、ジョブ内のすべてのタスクで行われる操作を記述します。</span><span class="sxs-lookup"><span data-stu-id="fd127-111">The total number of disk write operations made by all tasks in the job.</span></span></param>
        <param name="readIOGiB"><span data-ttu-id="fd127-112">GiB 内のデータの合計金額は、ジョブ内のすべてのタスクでは、ディスクから読み取られました。</span><span class="sxs-lookup"><span data-stu-id="fd127-112">The total amount of data in GiB read from disk by all tasks in the job.</span></span></param>
        <param name="writeIOGiB"><span data-ttu-id="fd127-113">ジョブ内のすべてのタスクによってディスクに書き込まれる GiB 内のデータの総量。</span><span class="sxs-lookup"><span data-stu-id="fd127-113">The total amount of data in GiB written to disk by all tasks in the job.</span></span></param>
        <param name="numSucceededTasks"><span data-ttu-id="fd127-114">指定された期間中にジョブが正常に完了したタスクの合計数。</span><span class="sxs-lookup"><span data-stu-id="fd127-114">The total number of tasks successfully completed in the job during the given time range.</span></span></param>
        <param name="numFailedTasks"><span data-ttu-id="fd127-115">指定された期間中に失敗したジョブのタスクの合計数。</span><span class="sxs-lookup"><span data-stu-id="fd127-115">The total number of tasks in the job that failed during the given time range.</span></span></param>
        <param name="numTaskRetries"><span data-ttu-id="fd127-116">指定された期間中にジョブ内のすべてのタスクでの再試行の合計数。</span><span class="sxs-lookup"><span data-stu-id="fd127-116">The total number of retries on all the tasks in the job during the given time range.</span></span></param>
        <param name="waitTime"><span data-ttu-id="fd127-117">ジョブ内のすべてのタスクの合計待機時間。</span><span class="sxs-lookup"><span data-stu-id="fd127-117">The total wait time of all tasks in the job.</span></span></param>
        <summary>
            <span data-ttu-id="fd127-118">JobStatistics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fd127-118">Initializes a new instance of the JobStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KernelCPUTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCPUTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCPUTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.KernelCPUTime" />
      <MemberSignature Language="VB.NET" Value="Public Property KernelCPUTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCPUTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.KernelCPUTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kernelCPUTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-119">取得または設定、カーネル モード CPU 時間の合計 (すべてのコアとすべてのコンピューティング ノード間で合計)、ジョブ内のすべてのタスクで使用します。</span><span class="sxs-lookup"><span data-stu-id="fd127-119">Gets or sets the total kernel mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-120">取得または設定する、統計の最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="fd127-120">Gets or sets the time at which the statistics were last updated.</span></span>
            <span data-ttu-id="fd127-121">すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。</span><span class="sxs-lookup"><span data-stu-id="fd127-121">All statistics are limited to the range between startTime and lastUpdateTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumFailedTasks">
      <MemberSignature Language="C#" Value="public long NumFailedTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumFailedTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumFailedTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property NumFailedTasks As Long" />
      <MemberSignature Language="F#" Value="member this.NumFailedTasks : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumFailedTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numFailedTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-122">取得または指定された期間中に失敗したジョブのタスクの合計数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-122">Gets or sets the total number of tasks in the job that failed during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fd127-123">終了コード 0 を返さずに、最大再試行回数が不足している場合、タスクが失敗します。</span><span class="sxs-lookup"><span data-stu-id="fd127-123">A task fails if it exhausts its maximum retry count without returning exit code 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumSucceededTasks">
      <MemberSignature Language="C#" Value="public long NumSucceededTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumSucceededTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumSucceededTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property NumSucceededTasks As Long" />
      <MemberSignature Language="F#" Value="member this.NumSucceededTasks : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumSucceededTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numSucceededTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-124">取得または指定された期間中にジョブが正常に完了したタスクの合計数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-124">Gets or sets the total number of tasks successfully completed in the job during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fd127-125">終了コード 0 が返された場合、タスクが正常に完了します。</span><span class="sxs-lookup"><span data-stu-id="fd127-125">A task completes successfully if it returns exit code 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumTaskRetries">
      <MemberSignature Language="C#" Value="public long NumTaskRetries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumTaskRetries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumTaskRetries" />
      <MemberSignature Language="VB.NET" Value="Public Property NumTaskRetries As Long" />
      <MemberSignature Language="F#" Value="member this.NumTaskRetries : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumTaskRetries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numTaskRetries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-126">取得または指定された期間中に、ジョブ内のすべてのタスクで再試行回数の合計数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-126">Gets or sets the total number of retries on all the tasks in the job during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readIOGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-127">取得または、ジョブ内のすべてのタスクによってディスクから読み取られた GiB でデータの合計サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-127">Gets or sets the total amount of data in GiB read from disk by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-128">取得またはディスクが、ジョブ内のすべてのタスクによって実行された読み取り操作の合計数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-128">Gets or sets the total number of disk read operations made by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-129">取得または統計の時間範囲の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-129">Gets or sets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-130">取得または統計情報の URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-130">Gets or sets the URL of the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCPUTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCPUTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCPUTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.UserCPUTime" />
      <MemberSignature Language="VB.NET" Value="Public Property UserCPUTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCPUTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.UserCPUTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userCPUTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-131">取得または設定、ユーザー モード CPU 時間の合計 (すべてのコアとすべてのコンピューティング ノード間で合計)、ジョブ内のすべてのタスクで使用します。</span><span class="sxs-lookup"><span data-stu-id="fd127-131">Gets or sets the total user mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobStatistics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fd127-132">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fd127-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd127-133">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd127-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WaitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-134">取得またはジョブのすべてのタスクの合計待機時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-134">Gets or sets the total wait time of all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fd127-135">タスクの待機時間は、タスクの作成とタスクの実行の開始までの経過時間として定義されます。</span><span class="sxs-lookup"><span data-stu-id="fd127-135">The wait time for a task is defined as the elapsed time between the creation of the task and the start of task execution.</span></span> <span data-ttu-id="fd127-136">(失敗したため、タスクが再試行された場合、待機時間は、最新のタスクの実行にかかる時間です。)この値は、アカウントの有効期間の統計情報です。 で報告のみジョブの統計は含まれません。</span><span class="sxs-lookup"><span data-stu-id="fd127-136">(If the task is retried due to failures, the wait time is the time to the most recent task execution.) This value is only reported in the account lifetime statistics; it is not included in the job statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="wallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-137">取得またはジョブのすべてのタスクの合計のウォール クロック時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-137">Gets or sets the total wall clock time of all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fd127-138">ウォール クロック時間は、タスクが完了すると、コンピューティング ノードで実行されている開始されたときにからの経過時間 (または最後に統計が更新されました、そのタスクが完了していない場合)。</span><span class="sxs-lookup"><span data-stu-id="fd127-138">The wall clock time is the elapsed time from when the task started running on a compute node to when it finished (or to the last time the statistics were updated, if the task had not finished by then).</span></span>
            <span data-ttu-id="fd127-139">タスクが再試行された場合は、すべてのタスク再試行のウォール クロック時間が含まれます。</span><span class="sxs-lookup"><span data-stu-id="fd127-139">If a task was retried, this includes the wall clock time of all the task retries.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeIOGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-140">取得または、ジョブ内のすべてのタスクによってディスクに書き込まれる GiB でデータの合計サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-140">Gets or sets the total amount of data in GiB written to disk by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd127-141">取得またはジョブのすべてのタスクによって行われたディスク書き込み操作の合計数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd127-141">Gets or sets the total number of disk write operations made by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>