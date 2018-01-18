<Type Name="BackupPolicy" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy">
  <TypeSignature Language="C#" Value="public class BackupPolicy : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupPolicy extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupPolicy&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type BackupPolicy = class&#xA;    inherit BaseModel" />
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
            <span data-ttu-id="3e35d-101">バックアップ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="3e35d-101">The backup policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-102">BackupPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-102">Initializes a new instance of the BackupPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupPolicy (System.Collections.Generic.IList&lt;string&gt; volumeIds, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; nextBackupTime = null, Nullable&lt;DateTime&gt; lastBackupTime = null, Nullable&lt;long&gt; schedulesCount = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; scheduledBackupStatus = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; backupPolicyCreationType = null, string ssmHostName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; volumeIds, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextBackupTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBackupTime, valuetype System.Nullable`1&lt;int64&gt; schedulesCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; scheduledBackupStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; backupPolicyCreationType, string ssmHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.#ctor(System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (volumeIds As IList(Of String), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional nextBackupTime As Nullable(Of DateTime) = null, Optional lastBackupTime As Nullable(Of DateTime) = null, Optional schedulesCount As Nullable(Of Long) = null, Optional scheduledBackupStatus As Nullable(Of ScheduledBackupStatus) = null, Optional backupPolicyCreationType As Nullable(Of BackupPolicyCreationType) = null, Optional ssmHostName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy : System.Collections.Generic.IList&lt;string&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy (volumeIds, id, name, type, kind, nextBackupTime, lastBackupTime, schedulesCount, scheduledBackupStatus, backupPolicyCreationType, ssmHostName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="volumeIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="nextBackupTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastBackupTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="schedulesCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="scheduledBackupStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt;" />
        <Parameter Name="backupPolicyCreationType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt;" />
        <Parameter Name="ssmHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="volumeIds"><span data-ttu-id="3e35d-103">パス、バックアップ ポリシーに含まれるボリュームの Id です。</span><span class="sxs-lookup"><span data-stu-id="3e35d-103">The path IDs of the volumes which are part of the backup policy.</span></span></param>
        <param name="id"><span data-ttu-id="3e35d-104">オブジェクトを一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="3e35d-104">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="3e35d-105">オブジェクトの名前。</span><span class="sxs-lookup"><span data-stu-id="3e35d-105">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="3e35d-106">オブジェクトの階層型です。</span><span class="sxs-lookup"><span data-stu-id="3e35d-106">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="3e35d-107">オブジェクトの種類。</span><span class="sxs-lookup"><span data-stu-id="3e35d-107">The Kind of the object.</span></span> <span data-ttu-id="3e35d-108">現在は Series8000 はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="3e35d-108">Currently only Series8000 is supported.</span></span> <span data-ttu-id="3e35d-109">使用可能な値が含まれます: 'Series8000'</span><span class="sxs-lookup"><span data-stu-id="3e35d-109">Possible values include: 'Series8000'</span></span></param>
        <param name="nextBackupTime"><span data-ttu-id="3e35d-110">バックアップ ポリシーの次回のバックアップの時刻。</span><span class="sxs-lookup"><span data-stu-id="3e35d-110">The time of the next backup for the backup policy.</span></span></param>
        <param name="lastBackupTime"><span data-ttu-id="3e35d-111">バックアップ ポリシーの最後のバックアップの時刻。</span><span class="sxs-lookup"><span data-stu-id="3e35d-111">The time of the last backup for the backup policy.</span></span></param>
        <param name="schedulesCount"><span data-ttu-id="3e35d-112">バックアップ ポリシーが含まれるスケジュールの数。</span><span class="sxs-lookup"><span data-stu-id="3e35d-112">The count of schedules the backup policy contains.</span></span></param>
        <param name="scheduledBackupStatus"><span data-ttu-id="3e35d-113">少なくとも 1 つのバックアップ ポリシーのスケジュールがアクティブであるかどうかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-113">Indicates whether atleast one of the schedules in the backup policy is active or not.</span></span> <span data-ttu-id="3e35d-114">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="3e35d-114">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <param name="backupPolicyCreationType"><span data-ttu-id="3e35d-115">バックアップ ポリシーの作成の種類。</span><span class="sxs-lookup"><span data-stu-id="3e35d-115">The backup policy creation type.</span></span> <span data-ttu-id="3e35d-116">SaaS または StorSimple Snapshot Manager をこの作成されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-116">Indicates whether this was created through SaaS or through StorSimple Snapshot Manager.</span></span> <span data-ttu-id="3e35d-117">使用可能な値が含まれます: 'BySaaS'、'BySSM'</span><span class="sxs-lookup"><span data-stu-id="3e35d-117">Possible values include: 'BySaaS', 'BySSM'</span></span></param>
        <param name="ssmHostName"><span data-ttu-id="3e35d-118">バックアップ ポリシーが StorSimple Snapshot Manager によって作成された場合、このフィールドは、StorSimple Snapshot Manager のホスト名を示します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-118">If the backup policy was created by StorSimple Snapshot Manager, then this field indicates the hostname of the StorSimple Snapshot Manager.</span></span></param>
        <summary>
            <span data-ttu-id="3e35d-119">BackupPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-119">Initializes a new instance of the BackupPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyCreationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; BackupPolicyCreationType { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; BackupPolicyCreationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.BackupPolicyCreationType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyCreationType As Nullable(Of BackupPolicyCreationType)" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyCreationType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.BackupPolicyCreationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupPolicyCreationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-120">バックアップ ポリシーの作成の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-120">Gets the backup policy creation type.</span></span> <span data-ttu-id="3e35d-121">SaaS または StorSimple Snapshot Manager をこの作成されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-121">Indicates whether this was created through SaaS or through StorSimple Snapshot Manager.</span></span>
            <span data-ttu-id="3e35d-122">使用可能な値が含まれます: 'BySaaS'、'BySSM'</span><span class="sxs-lookup"><span data-stu-id="3e35d-122">Possible values include: 'BySaaS', 'BySSM'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackupTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBackupTime { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBackupTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.LastBackupTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackupTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBackupTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.LastBackupTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastBackupTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-123">バックアップ ポリシーの最後のバックアップの時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-123">Gets the time of the last backup for the backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextBackupTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextBackupTime { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextBackupTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.NextBackupTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextBackupTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextBackupTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.NextBackupTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextBackupTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-124">バックアップ ポリシーのバックアップの次の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-124">Gets the time of the next backup for the backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledBackupStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; ScheduledBackupStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; ScheduledBackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.ScheduledBackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledBackupStatus As Nullable(Of ScheduledBackupStatus)" />
      <MemberSignature Language="F#" Value="member this.ScheduledBackupStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.ScheduledBackupStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduledBackupStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-125">取得では、少なくとも 1 つのバックアップ ポリシーのスケジュールがアクティブであるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-125">Gets indicates whether atleast one of the schedules in the backup policy is active or not.</span></span> <span data-ttu-id="3e35d-126">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="3e35d-126">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulesCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SchedulesCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SchedulesCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SchedulesCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulesCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SchedulesCount : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SchedulesCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schedulesCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-127">バックアップ ポリシーが含まれるスケジュールの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-127">Gets the count of schedules the backup policy contains.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SsmHostName">
      <MemberSignature Language="C#" Value="public string SsmHostName { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SsmHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SsmHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property SsmHostName As String" />
      <MemberSignature Language="F#" Value="member this.SsmHostName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SsmHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ssmHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-128">このフィールドは、StorSimple Snapshot Manager のホスト名を示すし、バックアップ ポリシーには、StorSimple Snapshot Manager によってが作成された場合を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-128">Gets if the backup policy was created by StorSimple Snapshot Manager, then this field indicates the hostname of the StorSimple Snapshot Manager.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupPolicy.Validate " />
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
            <span data-ttu-id="3e35d-129">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-129">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3e35d-130">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3e35d-130">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VolumeIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VolumeIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.VolumeIds" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VolumeIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.VolumeIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e35d-131">取得またはパス、バックアップ ポリシーに含まれるボリュームの Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e35d-131">Gets or sets the path IDs of the volumes which are part of the backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>