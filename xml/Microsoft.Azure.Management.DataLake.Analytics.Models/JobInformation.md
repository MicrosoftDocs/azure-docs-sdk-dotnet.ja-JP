<Type Name="JobInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation">
  <TypeSignature Language="C#" Value="public class JobInformation : Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobInformation extends Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobInformation&#xA;Inherits JobInformationBasic" />
  <TypeSignature Language="F#" Value="type JobInformation = class&#xA;    inherit JobInformationBasic" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ff924-101">拡張の Data Lake Analytics ジョブの特定のジョブを取得するときに返される情報のプロパティ。</span><span class="sxs-lookup"><span data-stu-id="ff924-101">The extended Data Lake Analytics job information properties returned when retrieving a specific job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ff924-102">JobInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ff924-102">Initializes a new instance of the JobInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformation (string name, Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties properties, Nullable&lt;Guid&gt; jobId = null, string submitter = null, Nullable&lt;int&gt; degreeOfParallelism = null, Nullable&lt;int&gt; priority = null, Nullable&lt;DateTimeOffset&gt; submitTime = null, Nullable&lt;DateTimeOffset&gt; startTime = null, Nullable&lt;DateTimeOffset&gt; endTime = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result = null, string logFolder = null, System.Collections.Generic.IList&lt;string&gt; logFilePatterns = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; errorMessage = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; stateAuditRecords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties properties, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; jobId, string submitter, valuetype System.Nullable`1&lt;int32&gt; degreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; priority, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; submitTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result, string logFolder, class System.Collections.Generic.IList`1&lt;string&gt; logFilePatterns, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; errorMessage, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; stateAuditRecords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.#ctor(System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties,System.Nullable{System.Guid},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobState},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult},System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As JobType, properties As JobProperties, Optional jobId As Nullable(Of Guid) = null, Optional submitter As String = null, Optional degreeOfParallelism As Nullable(Of Integer) = null, Optional priority As Nullable(Of Integer) = null, Optional submitTime As Nullable(Of DateTimeOffset) = null, Optional startTime As Nullable(Of DateTimeOffset) = null, Optional endTime As Nullable(Of DateTimeOffset) = null, Optional state As Nullable(Of JobState) = null, Optional result As Nullable(Of JobResult) = null, Optional logFolder As String = null, Optional logFilePatterns As IList(Of String) = null, Optional related As JobRelationshipProperties = null, Optional errorMessage As IList(Of JobErrorDetails) = null, Optional stateAuditRecords As IList(Of JobStateAuditRecord) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation : string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties * Nullable&lt;Guid&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation (name, type, properties, jobId, submitter, degreeOfParallelism, priority, submitTime, startTime, endTime, state, result, logFolder, logFilePatterns, related, errorMessage, stateAuditRecords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
        <Parameter Name="jobId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="submitter" Type="System.String" />
        <Parameter Name="degreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="submitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt;" />
        <Parameter Name="logFolder" Type="System.String" />
        <Parameter Name="logFilePatterns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="related" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties" />
        <Parameter Name="errorMessage" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;" />
        <Parameter Name="stateAuditRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ff924-103">ジョブのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="ff924-103">the friendly name of the job.</span></span></param>
        <param name="type"><span data-ttu-id="ff924-104">(Hive または USql) は、現在のジョブのジョブの種類。</span><span class="sxs-lookup"><span data-stu-id="ff924-104">the job type of the current job (Hive or USql).</span></span>
            <span data-ttu-id="ff924-105">使用可能な値が含まれます: 'USql'、'ハイブ'</span><span class="sxs-lookup"><span data-stu-id="ff924-105">Possible values include: 'USql', 'Hive'</span></span></param>
        <param name="properties"><span data-ttu-id="ff924-106">ジョブの特定プロパティです。</span><span class="sxs-lookup"><span data-stu-id="ff924-106">the job specific properties.</span></span></param>
        <param name="jobId"><span data-ttu-id="ff924-107">ジョブの一意の識別子 (GUID)。</span><span class="sxs-lookup"><span data-stu-id="ff924-107">the job's unique identifier (a GUID).</span></span></param>
        <param name="submitter"><span data-ttu-id="ff924-108">ユーザーまたはジョブを送信するアカウント。</span><span class="sxs-lookup"><span data-stu-id="ff924-108">the user or account that submitted the job.</span></span></param>
        <param name="degreeOfParallelism"><span data-ttu-id="ff924-109">このジョブに対して使用される並列処理の次数。</span><span class="sxs-lookup"><span data-stu-id="ff924-109">the degree of parallelism used for this job.</span></span> <span data-ttu-id="ff924-110">場合 1 を 0 未満の値の設定は既定値は 0 より大きくにあります。</span><span class="sxs-lookup"><span data-stu-id="ff924-110">This must be greater than 0, if set to less than 0 it will default to 1.</span></span></param>
        <param name="priority"><span data-ttu-id="ff924-111">現在のジョブの優先度の値。</span><span class="sxs-lookup"><span data-stu-id="ff924-111">the priority value for the current job.</span></span>
            <span data-ttu-id="ff924-112">数値が小さいほど優先順位が高いがあります。</span><span class="sxs-lookup"><span data-stu-id="ff924-112">Lower numbers have a higher priority.</span></span> <span data-ttu-id="ff924-113">、既定では、ジョブは、1000 の優先順位を持ちます。</span><span class="sxs-lookup"><span data-stu-id="ff924-113">By default, a job has a priority of 1000.</span></span> <span data-ttu-id="ff924-114">これは、0 より大きくなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ff924-114">This must be greater than 0.</span></span></param>
        <param name="submitTime"><span data-ttu-id="ff924-115">ジョブがサービスに送信された時刻。</span><span class="sxs-lookup"><span data-stu-id="ff924-115">the time the job was submitted to the service.</span></span></param>
        <param name="startTime"><span data-ttu-id="ff924-116">ジョブの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="ff924-116">the start time of the job.</span></span></param>
        <param name="endTime"><span data-ttu-id="ff924-117">ジョブの完了時間。</span><span class="sxs-lookup"><span data-stu-id="ff924-117">the completion time of the job.</span></span></param>
        <param name="state"><span data-ttu-id="ff924-118">ジョブの状態。</span><span class="sxs-lookup"><span data-stu-id="ff924-118">the job state.</span></span> <span data-ttu-id="ff924-119">ジョブが終了状態になった場合、詳細結果とエラー メッセージを参照してください。</span><span class="sxs-lookup"><span data-stu-id="ff924-119">When the job is in the Ended state, refer to Result and ErrorMessage for details.</span></span> <span data-ttu-id="ff924-120">使用可能な値が含まれます: '許可'、'コンパイル'、'終了'、'New'、'Queued'、'実行中、'スケジューリング'、' 開始'、'一時停止中'、'WaitingForCapacity'</span><span class="sxs-lookup"><span data-stu-id="ff924-120">Possible values include: 'Accepted', 'Compiling', 'Ended', 'New', 'Queued', 'Running', 'Scheduling', 'Starting', 'Paused', 'WaitingForCapacity'</span></span></param>
        <param name="result"><span data-ttu-id="ff924-121">ジョブの実行や、現在実行中のジョブの結果の結果。</span><span class="sxs-lookup"><span data-stu-id="ff924-121">the result of job execution or the current result of the running job.</span></span> <span data-ttu-id="ff924-122">使用可能な値が含まれます 'None'、'成功'、'キャンセル'、'失敗'。</span><span class="sxs-lookup"><span data-stu-id="ff924-122">Possible values include: 'None', 'Succeeded', 'Cancelled', 'Failed'</span></span></param>
        <param name="logFolder"><span data-ttu-id="ff924-123">次の形式で使用するログ フォルダーのパス: 含む://&lt;accountName&gt;.azuredatalakestore.net/system/jobservice/jobs/Usql/2016/03/13/17/18/5fe51957-93bc-4de0-8ddc-c5a4753b068b/logs/ です。</span><span class="sxs-lookup"><span data-stu-id="ff924-123">the log folder path to use in the following format: adl://&lt;accountName&gt;.azuredatalakestore.net/system/jobservice/jobs/Usql/2016/03/13/17/18/5fe51957-93bc-4de0-8ddc-c5a4753b068b/logs/.</span></span></param>
        <param name="logFilePatterns"><span data-ttu-id="ff924-124">logFolder 内を検索するログ ファイル名パターンの一覧。</span><span class="sxs-lookup"><span data-stu-id="ff924-124">the list of log file name patterns to find in the logFolder.</span></span> <span data-ttu-id="ff924-125">'*' は許可されている唯一の一致する文字。形式の例: jobExecution*.log または*mylog*.txt</span><span class="sxs-lookup"><span data-stu-id="ff924-125">'*' is the only matching character allowed. Example format: jobExecution*.log or *mylog*.txt</span></span></param>
        <param name="related"><span data-ttu-id="ff924-126">定期的なジョブ関係情報のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="ff924-126">the recurring job relationship information properties.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="ff924-127">ジョブが失敗した場合、ジョブのエラー メッセージの詳細。</span><span class="sxs-lookup"><span data-stu-id="ff924-127">the error message details for the job, if the job failed.</span></span></param>
        <param name="stateAuditRecords"><span data-ttu-id="ff924-128">ジョブの状態は、さまざまな操作でこのジョブで実行されたときにサイズを示すレコードを監査します。</span><span class="sxs-lookup"><span data-stu-id="ff924-128">the job state audit records, indicating when various operations have been performed on this job.</span></span></param>
        <summary>
            <span data-ttu-id="ff924-129">JobInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ff924-129">Initializes a new instance of the JobInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As IList(Of JobErrorDetails)" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff924-130">エラー メッセージの詳細を取得、ジョブ、ジョブが失敗した場合。</span><span class="sxs-lookup"><span data-stu-id="ff924-130">Gets the error message details for the job, if the job failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As JobProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff924-131">取得またはジョブを特定のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="ff924-131">Gets or sets the job specific properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateAuditRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; StateAuditRecords { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; StateAuditRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.StateAuditRecords" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateAuditRecords As IList(Of JobStateAuditRecord)" />
      <MemberSignature Language="F#" Value="member this.StateAuditRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.StateAuditRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateAuditRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff924-132">ジョブのジョブのさまざまな操作が実行されたときにサイズを示す状態監査レコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="ff924-132">Gets the job state audit records, indicating when various operations have been performed on this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="jobInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ff924-133">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ff924-133">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ff924-134">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ff924-134">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>