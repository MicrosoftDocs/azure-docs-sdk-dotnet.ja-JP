<Type Name="BackupSchedule" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule">
  <TypeSignature Language="C#" Value="public class BackupSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupSchedule" />
  <TypeSignature Language="F#" Value="type BackupSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3a986-101">バックアップ スケジュールの説明です。</span><span class="sxs-lookup"><span data-stu-id="3a986-101">Description of a backup schedule.</span></span> <span data-ttu-id="3a986-102">どのくらいの頻度、バックアップ実行について説明し、保有期間ポリシーある必要があります。</span><span class="sxs-lookup"><span data-stu-id="3a986-102">Describes how often should be the backup performed and what should be the retention policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a986-103">BackupSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3a986-103">Initializes a new instance of the BackupSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule (int frequencyInterval, Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit frequencyUnit, bool keepAtLeastOneBackup, int retentionPeriodInDays, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; lastExecutionTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 frequencyInterval, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit frequencyUnit, bool keepAtLeastOneBackup, int32 retentionPeriodInDays, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastExecutionTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.#ctor(System.Int32,Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit,System.Boolean,System.Int32,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule : int * Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit * bool * int * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule (frequencyInterval, frequencyUnit, keepAtLeastOneBackup, retentionPeriodInDays, startTime, lastExecutionTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="frequencyInterval" Type="System.Int32" />
        <Parameter Name="frequencyUnit" Type="Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit" />
        <Parameter Name="keepAtLeastOneBackup" Type="System.Boolean" />
        <Parameter Name="retentionPeriodInDays" Type="System.Int32" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastExecutionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="frequencyInterval"><span data-ttu-id="3a986-104">どのくらいの頻度は、バックアップを実行する必要があります (例: これは、バックアップを毎週の 7 に設定する必要があり、FrequencyUnit は 1 日に設定する必要があります)</span><span class="sxs-lookup"><span data-stu-id="3a986-104">How often should be the backup executed (e.g. for weekly backup, this should be set to 7 and FrequencyUnit should be set to Day)</span></span></param>
        <param name="frequencyUnit"><span data-ttu-id="3a986-105">時間の単位をどのくらいの頻度、バックアップを実行するか (例: これは、バックアップを毎週の日に設定する必要があり、FrequencyInterval を 7 に設定する必要があります)。</span><span class="sxs-lookup"><span data-stu-id="3a986-105">The unit of time for how often should be the backup executed (e.g. for weekly backup, this should be set to Day and FrequencyInterval should be set to 7).</span></span> <span data-ttu-id="3a986-106">使用可能な値が含まれます: '日付'、'Hour'</span><span class="sxs-lookup"><span data-stu-id="3a986-106">Possible values include: 'Day', 'Hour'</span></span></param>
        <param name="keepAtLeastOneBackup"><span data-ttu-id="3a986-107">True の場合は、保有期間ポリシー必要があります常に保持するには、少なくとも 1 つのバックアップ ストレージ アカウント内に関係なくどれだけ古いです。false それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="3a986-107">True if the retention policy should always keep at least one backup in the storage account, regardless how old it is; false otherwise.</span></span></param>
        <param name="retentionPeriodInDays"><span data-ttu-id="3a986-108">何日後にバックアップを削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3a986-108">After how many days backups should be deleted.</span></span></param>
        <param name="startTime"><span data-ttu-id="3a986-109">ときに、スケジュールは、作業を開始する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3a986-109">When the schedule should start working.</span></span></param>
        <param name="lastExecutionTime"><span data-ttu-id="3a986-110">前回のスケジュールがトリガーされました。</span><span class="sxs-lookup"><span data-stu-id="3a986-110">Last time when this schedule was triggered.</span></span></param>
        <summary>
            <span data-ttu-id="3a986-111">BackupSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3a986-111">Initializes a new instance of the BackupSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrequencyInterval">
      <MemberSignature Language="C#" Value="public int FrequencyInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrequencyInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property FrequencyInterval As Integer" />
      <MemberSignature Language="F#" Value="member this.FrequencyInterval : int with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frequencyInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a986-112">どのくらいの頻度を取得または設定が実行されたバックアップをする必要があります (例: これは、バックアップを毎週の 7 に設定する必要があり、FrequencyUnit は 1 日に設定する必要があります)</span><span class="sxs-lookup"><span data-stu-id="3a986-112">Gets or sets how often should be the backup executed (e.g. for weekly backup, this should be set to 7 and FrequencyUnit should be set to Day)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrequencyUnit">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit FrequencyUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit FrequencyUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property FrequencyUnit As FrequencyUnit" />
      <MemberSignature Language="F#" Value="member this.FrequencyUnit : Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.FrequencyUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frequencyUnit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.FrequencyUnit</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a986-113">取得または時間の単位を設定する頻度、バックアップを実行するか (例: これは、バックアップを毎週の日に設定する必要があり、FrequencyInterval を 7 に設定する必要があります)。</span><span class="sxs-lookup"><span data-stu-id="3a986-113">Gets or sets the unit of time for how often should be the backup executed (e.g. for weekly backup, this should be set to Day and FrequencyInterval should be set to 7).</span></span> <span data-ttu-id="3a986-114">使用可能な値が含まれます: '日付'、'Hour'</span><span class="sxs-lookup"><span data-stu-id="3a986-114">Possible values include: 'Day', 'Hour'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAtLeastOneBackup">
      <MemberSignature Language="C#" Value="public bool KeepAtLeastOneBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool KeepAtLeastOneBackup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.KeepAtLeastOneBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAtLeastOneBackup As Boolean" />
      <MemberSignature Language="F#" Value="member this.KeepAtLeastOneBackup : bool with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.KeepAtLeastOneBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keepAtLeastOneBackup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a986-115">取得または設定の保持ポリシー必要があります常に保持するには、少なくとも 1 つのバックアップ ストレージ アカウント内に関係なく true をどれだけ古いです。false それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="3a986-115">Gets or sets true if the retention policy should always keep at least one backup in the storage account, regardless how old it is; false otherwise.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastExecutionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.LastExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastExecutionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastExecutionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.LastExecutionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastExecutionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a986-116">このスケジュールがトリガーされた最終時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="3a986-116">Gets last time when this schedule was triggered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPeriodInDays">
      <MemberSignature Language="C#" Value="public int RetentionPeriodInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetentionPeriodInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.RetentionPeriodInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPeriodInDays As Integer" />
      <MemberSignature Language="F#" Value="member this.RetentionPeriodInDays : int with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.RetentionPeriodInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionPeriodInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a986-117">取得または設定後何日バックアップを削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3a986-117">Gets or sets after how many days backups should be deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a986-118">取得または設定、スケジュールは、作業を開始するときにします。</span><span class="sxs-lookup"><span data-stu-id="3a986-118">Gets or sets when the schedule should start working.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a986-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3a986-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3a986-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3a986-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>