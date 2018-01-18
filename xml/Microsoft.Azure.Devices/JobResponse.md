<Type Name="JobResponse" FullName="Microsoft.Azure.Devices.JobResponse">
  <TypeSignature Language="C#" Value="public class JobResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class JobResponse" />
  <TypeSignature Language="F#" Value="type JobResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c3e3a-101">現在のジョブ レポート フェッチしたときに、します。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-101">Provides current job report when fetched</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudToDeviceMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.CloudToDeviceMethod CloudToDeviceMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.CloudToDeviceMethod CloudToDeviceMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.CloudToDeviceMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudToDeviceMethod As CloudToDeviceMethod" />
      <MemberSignature Language="F#" Value="member this.CloudToDeviceMethod : Microsoft.Azure.Devices.CloudToDeviceMethod with get, set" Usage="Microsoft.Azure.Devices.JobResponse.CloudToDeviceMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="cloudToDeviceMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.CloudToDeviceMethod</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-102">JobType が cloudToDeviceMethod がかどうかに必要です。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-102">Required if jobType is cloudToDeviceMethod.</span></span>
            <span data-ttu-id="c3e3a-103">メソッドの型およびパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-103">The method type and parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.CreatedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Devices.JobResponse.CreatedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-104">ジョブの開始時刻 (utc) をスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-104">Scheduled job start time in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.JobResponse.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="deviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-105">この応答に関連する deviceId です。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-105">The deviceId related to this response.</span></span>
            <span data-ttu-id="c3e3a-106">(例: 親オーケストレーション) の場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-106">It can be null (e.g. in case of a parent orchestration).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceJobStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.DeviceJobStatistics DeviceJobStatistics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.DeviceJobStatistics DeviceJobStatistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.DeviceJobStatistics" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceJobStatistics As DeviceJobStatistics" />
      <MemberSignature Language="F#" Value="member this.DeviceJobStatistics : Microsoft.Azure.Devices.DeviceJobStatistics with get, set" Usage="Microsoft.Azure.Devices.JobResponse.DeviceJobStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="deviceJobStatistics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeviceJobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-107">ジョブ内のデバイス数が異なる</span><span class="sxs-lookup"><span data-stu-id="c3e3a-107">Different number of devices in the job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.EndTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Devices.JobResponse.EndTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-108">システムによって生成されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-108">System generated.</span></span>  <span data-ttu-id="c3e3a-109">作成時に無視されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-109">Ignored at creation.</span></span>
            <span data-ttu-id="c3e3a-110">処理ジョブを停止した時間を表します。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-110">Represents the time the job stopped processing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public string FailureReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailureReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureReason As String" />
      <MemberSignature Language="F#" Value="member this.FailureReason : string with get, set" Usage="Microsoft.Azure.Devices.JobResponse.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="failureReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-111">システムによって生成されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-111">System generated.</span></span>  <span data-ttu-id="c3e3a-112">作成時に無視されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-112">Ignored at creation.</span></span>
            <span data-ttu-id="c3e3a-113">場合の状態エラー、このは、理由を含む文字列を = = です。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-113">If status == failure, this represents a string containing the reason.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string" Usage="Microsoft.Azure.Devices.JobResponse.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-114">システムによって生成されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-114">System generated.</span></span>  <span data-ttu-id="c3e3a-115">作成時に無視されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-115">Ignored at creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxExecutionTimeInSeconds">
      <MemberSignature Language="C#" Value="public long MaxExecutionTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxExecutionTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.MaxExecutionTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxExecutionTimeInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.MaxExecutionTimeInSeconds : int64 with get, set" Usage="Microsoft.Azure.Devices.JobResponse.MaxExecutionTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate, PropertyName="maxExecutionTimeInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-116">までに最大実行時間</span><span class="sxs-lookup"><span data-stu-id="c3e3a-116">Max execution time in secounds</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentJobId">
      <MemberSignature Language="C#" Value="public string ParentJobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParentJobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.ParentJobId" />
      <MemberSignature Language="VB.NET" Value="Public Property ParentJobId As String" />
      <MemberSignature Language="F#" Value="member this.ParentJobId : string with get, set" Usage="Microsoft.Azure.Devices.JobResponse.ParentJobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="parentJobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-117">存在する場合、親オーケストレーションのジョブ Id。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-117">The jobId of the parent orchestration, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryCondition">
      <MemberSignature Language="C#" Value="public string QueryCondition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueryCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.QueryCondition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryCondition As String" />
      <MemberSignature Language="F#" Value="member this.QueryCondition : string" Usage="Microsoft.Azure.Devices.JobResponse.QueryCondition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="queryCondition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-118">デバイス クエリ条件です。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-118">Device query condition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.StartTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Devices.JobResponse.StartTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-119">システムによって生成されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-119">System generated.</span></span>  <span data-ttu-id="c3e3a-120">作成時に無視されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-120">Ignored at creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.JobStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.JobStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As JobStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Devices.JobStatus" Usage="Microsoft.Azure.Devices.JobResponse.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-121">システムによって生成されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-121">System generated.</span></span>  <span data-ttu-id="c3e3a-122">作成時に無視されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-122">Ignored at creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusMessage">
      <MemberSignature Language="C#" Value="public string StatusMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.StatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusMessage As String" />
      <MemberSignature Language="F#" Value="member this.StatusMessage : string with get, set" Usage="Microsoft.Azure.Devices.JobResponse.StatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="statusMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-123">システムによって生成されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-123">System generated.</span></span>  <span data-ttu-id="c3e3a-124">作成時に無視されます。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-124">Ignored at creation.</span></span>
            <span data-ttu-id="c3e3a-125">ジョブの実行に関する状態メッセージを含む文字列を表します。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-125">Represents a string containing a message with status about the job execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.JobType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.JobType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As JobType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Devices.JobType" Usage="Microsoft.Azure.Devices.JobResponse.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-126">必須。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-126">Required.</span></span>
            <span data-ttu-id="c3e3a-127">実行するジョブの種類。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-127">The type of job to execute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Shared.Twin UpdateTwin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Shared.Twin UpdateTwin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobResponse.UpdateTwin" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateTwin As Twin" />
      <MemberSignature Language="F#" Value="member this.UpdateTwin : Microsoft.Azure.Devices.Shared.Twin with get, set" Usage="Microsoft.Azure.Devices.JobResponse.UpdateTwin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="updateTwin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.Twin</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3e3a-128">JobType が updateTwin がかどうかに必要です。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-128">Required if jobType is updateTwin.</span></span>
            <span data-ttu-id="c3e3a-129">更新ツイン タグと必要なプロパティです。</span><span class="sxs-lookup"><span data-stu-id="c3e3a-129">The Update Twin tags and desired properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>