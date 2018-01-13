<Type Name="JobExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobExecutionInformation = class" />
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
            <span data-ttu-id="7ed40-101">Azure Batch のサービスでジョブの実行に関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="7ed40-101">Contains information about the execution of a job in the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.#ctor" />
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
            <span data-ttu-id="7ed40-102">JobExecutionInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-102">Initializes a new instance of the JobExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobExecutionInformation (DateTime startTime, Nullable&lt;DateTime&gt; endTime = null, string poolId = null, Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError schedulingError = null, string terminateReason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string poolId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError schedulingError, string terminateReason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.#ctor(System.DateTime,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, Optional endTime As Nullable(Of DateTime) = null, Optional poolId As String = null, Optional schedulingError As JobSchedulingError = null, Optional terminateReason As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation : DateTime * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError * string -&gt; Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation (startTime, endTime, poolId, schedulingError, terminateReason)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="schedulingError" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError" />
        <Parameter Name="terminateReason" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="7ed40-103">ジョブの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="7ed40-103">The start time of the job.</span></span></param>
        <param name="endTime"><span data-ttu-id="7ed40-104">ジョブの完了時間。</span><span class="sxs-lookup"><span data-stu-id="7ed40-104">The completion time of the job.</span></span></param>
        <param name="poolId"><span data-ttu-id="7ed40-105">このジョブが割り当てられているプールの ID。</span><span class="sxs-lookup"><span data-stu-id="7ed40-105">The ID of the pool to which this job is assigned.</span></span></param>
        <param name="schedulingError"><span data-ttu-id="7ed40-106">ジョブを開始時にサービスで発生したエラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="7ed40-106">Details of any error encountered by the service in starting the job.</span></span></param>
        <param name="terminateReason"><span data-ttu-id="7ed40-107">ジョブの理由を説明する文字列が終了しました。</span><span class="sxs-lookup"><span data-stu-id="7ed40-107">A string describing the reason the job ended.</span></span></param>
        <summary>
            <span data-ttu-id="7ed40-108">JobExecutionInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-108">Initializes a new instance of the JobExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ed40-109">取得またはジョブの完了時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-109">Gets or sets the completion time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7ed40-110">ジョブが完了した状態の場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="7ed40-110">This property is set only if the job is in the completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ed40-111">取得または、このジョブが割り当てられているプールの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-111">Gets or sets the ID of the pool to which this job is assigned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7ed40-112">この要素には、ジョブが割り当てられている実際のプールが含まれています。</span><span class="sxs-lookup"><span data-stu-id="7ed40-112">This element contains the actual pool where the job is assigned.</span></span>
            <span data-ttu-id="7ed40-113">サービスからジョブの詳細を取得する場合もジョブが追加または更新されたときに、プールから構成データを含む poolInfo 要素を格納します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-113">When you get job details from the service, they also contain a poolInfo element, which contains the pool configuration data from when the job was added or updated.</span></span> <span data-ttu-id="7ed40-114">その poolInfo 要素では、poolId 要素もあります。</span><span class="sxs-lookup"><span data-stu-id="7ed40-114">That poolInfo element may also contain a poolId element.</span></span> <span data-ttu-id="7ed40-115">その場合、2 つの Id は同じです。</span><span class="sxs-lookup"><span data-stu-id="7ed40-115">If it does, the two IDs are the same.</span></span> <span data-ttu-id="7ed40-116">そうでない場合、自動プールで実行されたジョブと、このプロパティには、その自動プールの ID が含まれています。 を意味します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-116">If it does not, it means the job ran on an auto pool, and this property contains the ID of that auto pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError SchedulingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError SchedulingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.SchedulingError" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulingError As JobSchedulingError" />
      <MemberSignature Language="F#" Value="member this.SchedulingError : Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.SchedulingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulingError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSchedulingError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ed40-117">取得またはジョブを開始時にサービスで発生したエラーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-117">Gets or sets details of any error encountered by the service in starting the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7ed40-118">ジョブの開始中にエラーがない場合、このプロパティは設定されません。</span><span class="sxs-lookup"><span data-stu-id="7ed40-118">This property is not set if there was no error starting the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.StartTime" />
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
            <span data-ttu-id="7ed40-119">取得またはジョブの開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-119">Gets or sets the start time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7ed40-120">これは、ジョブの作成日時です。</span><span class="sxs-lookup"><span data-stu-id="7ed40-120">This is the time at which the job was created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateReason">
      <MemberSignature Language="C#" Value="public string TerminateReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TerminateReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.TerminateReason" />
      <MemberSignature Language="VB.NET" Value="Public Property TerminateReason As String" />
      <MemberSignature Language="F#" Value="member this.TerminateReason : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.TerminateReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="terminateReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ed40-121">取得またはジョブが終了した理由を説明する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-121">Gets or sets a string describing the reason the job ended.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7ed40-122">ジョブが完了した状態の場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="7ed40-122">This property is set only if the job is in the completed state.</span></span> <span data-ttu-id="7ed40-123">次のように設定、理由、バッチ サービスは、ジョブを終了する場合、: JMComplete - ジョブ マネージャー タスクが完了し、killJobOnCompletion の設定を true にします。</span><span class="sxs-lookup"><span data-stu-id="7ed40-123">If the Batch service terminates the job, it sets the reason as follows: JMComplete - the Job Manager task completed, and killJobOnCompletion was set to true.</span></span> <span data-ttu-id="7ed40-124">MaxWallClockTimeExpiry - ジョブは、その maxWallClockTime 制約に達しました。</span><span class="sxs-lookup"><span data-stu-id="7ed40-124">MaxWallClockTimeExpiry - the job reached its maxWallClockTime constraint.</span></span> <span data-ttu-id="7ed40-125">TerminateJobSchedule - ジョブは、スケジュールの一部として実行し、スケジュールが終了します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-125">TerminateJobSchedule - the job ran as part of a schedule, and the schedule terminated.</span></span>
            <span data-ttu-id="7ed40-126">AllTasksComplete - ジョブの onAllTasksComplete 属性に設定されている terminateJob、し、ジョブ内のすべてのタスクが完了します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-126">AllTasksComplete - the job's onAllTasksComplete attribute is set to terminateJob, and all tasks in the job are complete.</span></span> <span data-ttu-id="7ed40-127">TaskFailed - ジョブの onTaskFailure 属性は、performExitOptionsJobAction、および terminateJob の jobAction の指定した終了条件に失敗したジョブのタスクに設定されます。</span><span class="sxs-lookup"><span data-stu-id="7ed40-127">TaskFailed - the job's onTaskFailure attribute is set to performExitOptionsJobAction, and a task in the job failed with an exit condition that specified a jobAction of terminateJob.</span></span> <span data-ttu-id="7ed40-128">その他の文字列は、'ジョブを終了' 操作の呼び出しで指定されたユーザー定義の理由です。</span><span class="sxs-lookup"><span data-stu-id="7ed40-128">Any other string is a user-defined reason specified in a call to the 'Terminate a job' operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobExecutionInformation.Validate " />
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
            <span data-ttu-id="7ed40-129">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7ed40-129">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7ed40-130">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7ed40-130">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>