<Type Name="BackupSchedule" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule">
  <TypeSignature Language="C#" Value="public class BackupSchedule : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupSchedule extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupSchedule&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type BackupSchedule = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bdcf3-101">バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-101">The backup schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-102">BackupSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-102">Initializes a new instance of the BackupSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule (Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence scheduleRecurrence, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType backupType, long retentionCount, DateTime startTime, Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus scheduleStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; lastSuccessfulRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence scheduleRecurrence, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType backupType, int64 retentionCount, valuetype System.DateTime startTime, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus scheduleStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastSuccessfulRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType,System.Int64,System.DateTime,Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType * int64 * DateTime * Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule (scheduleRecurrence, backupType, retentionCount, startTime, scheduleStatus, id, name, type, kind, lastSuccessfulRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scheduleRecurrence" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence" />
        <Parameter Name="backupType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType" />
        <Parameter Name="retentionCount" Type="System.Int64" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="scheduleStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="lastSuccessfulRun" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="scheduleRecurrence"><span data-ttu-id="bdcf3-103">スケジュールの繰り返しです。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-103">The schedule recurrence.</span></span></param>
        <param name="backupType"><span data-ttu-id="bdcf3-104">実行する必要があるバックアップの種類。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-104">The type of backup which needs to be taken.</span></span> <span data-ttu-id="bdcf3-105">使用可能な値が含まれます: 'LocalSnapshot'、'CloudSnapshot'</span><span class="sxs-lookup"><span data-stu-id="bdcf3-105">Possible values include: 'LocalSnapshot', 'CloudSnapshot'</span></span></param>
        <param name="retentionCount"><span data-ttu-id="bdcf3-106">保持されるバックアップの数。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-106">The number of backups to be retained.</span></span></param>
        <param name="startTime"><span data-ttu-id="bdcf3-107">スケジュールの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-107">The start time of the schedule.</span></span></param>
        <param name="scheduleStatus"><span data-ttu-id="bdcf3-108">スケジュールの状態。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-108">The schedule status.</span></span> <span data-ttu-id="bdcf3-109">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="bdcf3-109">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="id"><span data-ttu-id="bdcf3-110">オブジェクトを一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-110">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="bdcf3-111">オブジェクトの名前。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-111">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="bdcf3-112">オブジェクトの階層型です。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-112">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="bdcf3-113">オブジェクトの種類。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-113">The Kind of the object.</span></span> <span data-ttu-id="bdcf3-114">現在は Series8000 はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-114">Currently only Series8000 is supported.</span></span> <span data-ttu-id="bdcf3-115">使用可能な値が含まれます: 'Series8000'</span><span class="sxs-lookup"><span data-stu-id="bdcf3-115">Possible values include: 'Series8000'</span></span></param>
        <param name="lastSuccessfulRun"><span data-ttu-id="bdcf3-116">最後のバックアップ スケジュールのトリガーされたを実行します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-116">The last successful backup run which was triggered for the schedule.</span></span></param>
        <summary>
            <span data-ttu-id="bdcf3-117">BackupSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-117">Initializes a new instance of the BackupSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As BackupType" />
      <MemberSignature Language="F#" Value="member this.BackupType : Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.BackupType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-118">取得または実行する必要があるバックアップの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-118">Gets or sets the type of backup which needs to be taken.</span></span> <span data-ttu-id="bdcf3-119">使用可能な値が含まれます: 'LocalSnapshot'、'CloudSnapshot'</span><span class="sxs-lookup"><span data-stu-id="bdcf3-119">Possible values include: 'LocalSnapshot', 'CloudSnapshot'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSuccessfulRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastSuccessfulRun { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastSuccessfulRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.LastSuccessfulRun" />
      <MemberSignature Language="VB.NET" Value="Public Property LastSuccessfulRun As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastSuccessfulRun : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.LastSuccessfulRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastSuccessfulRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-120">実行のスケジュールがトリガーされた最後のバックアップを取得します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-120">Gets the last successful backup run which was triggered for the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionCount">
      <MemberSignature Language="C#" Value="public long RetentionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RetentionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.RetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.RetentionCount : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.RetentionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-121">取得または保持されるバックアップの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-121">Gets or sets the number of backups to be retained.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRecurrence">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence ScheduleRecurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence ScheduleRecurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleRecurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRecurrence As ScheduleRecurrence" />
      <MemberSignature Language="F#" Value="member this.ScheduleRecurrence : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleRecurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduleRecurrence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-122">取得またはスケジュールの繰り返しを設定します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-122">Gets or sets the schedule recurrence.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus ScheduleStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus ScheduleStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleStatus As ScheduleStatus" />
      <MemberSignature Language="F#" Value="member this.ScheduleStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduleStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-123">取得またはスケジュールの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-123">Gets or sets the schedule status.</span></span> <span data-ttu-id="bdcf3-124">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="bdcf3-124">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-125">取得またはスケジュールの開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-125">Gets or sets the start time of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bdcf3-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bdcf3-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bdcf3-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>