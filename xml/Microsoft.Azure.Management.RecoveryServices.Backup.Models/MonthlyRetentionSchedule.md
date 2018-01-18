<Type Name="MonthlyRetentionSchedule" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule">
  <TypeSignature Language="C#" Value="public class MonthlyRetentionSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MonthlyRetentionSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class MonthlyRetentionSchedule" />
  <TypeSignature Language="F#" Value="type MonthlyRetentionSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68094-101">毎月の保有期間のスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="68094-101">Monthly retention schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonthlyRetentionSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68094-102">MonthlyRetentionSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="68094-102">Initializes a new instance of the MonthlyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonthlyRetentionSchedule (string retentionScheduleFormatType = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat retentionScheduleDaily = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat retentionScheduleWeekly = null, System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; retentionTimes = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration retentionDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string retentionScheduleFormatType, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat retentionScheduleDaily, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat retentionScheduleWeekly, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; retentionTimes, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration retentionDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.#ctor(System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat,Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat,System.Collections.Generic.IList{System.Nullable{System.DateTime}},Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule : string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat * Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat * System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule (retentionScheduleFormatType, retentionScheduleDaily, retentionScheduleWeekly, retentionTimes, retentionDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retentionScheduleFormatType" Type="System.String" />
        <Parameter Name="retentionScheduleDaily" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat" />
        <Parameter Name="retentionScheduleWeekly" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat" />
        <Parameter Name="retentionTimes" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.DateTime&gt;&gt;" />
        <Parameter Name="retentionDuration" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration" />
      </Parameters>
      <Docs>
        <param name="retentionScheduleFormatType"><span data-ttu-id="68094-103">月単位の保有ポリシーの保有期間のスケジュールの形式の種類。</span><span class="sxs-lookup"><span data-stu-id="68094-103">Retention schedule format type for monthly retention policy.</span></span> <span data-ttu-id="68094-104">使用可能な値が含まれます: '無効'、'毎日'、'毎週'</span><span class="sxs-lookup"><span data-stu-id="68094-104">Possible values include: 'Invalid', 'Daily', 'Weekly'</span></span></param>
        <param name="retentionScheduleDaily"><span data-ttu-id="68094-105">毎月の保持ポリシーの毎日の保存形式です。</span><span class="sxs-lookup"><span data-stu-id="68094-105">Daily retention format for monthly retention policy.</span></span></param>
        <param name="retentionScheduleWeekly"><span data-ttu-id="68094-106">毎月の保持ポリシーの毎週の保存形式です。</span><span class="sxs-lookup"><span data-stu-id="68094-106">Weekly retention format for monthly retention policy.</span></span></param>
        <param name="retentionTimes"><span data-ttu-id="68094-107">保有ポリシーの保存期間。</span><span class="sxs-lookup"><span data-stu-id="68094-107">Retention times of retention policy.</span></span></param>
        <param name="retentionDuration"><span data-ttu-id="68094-108">保有ポリシーの保有期間です。</span><span class="sxs-lookup"><span data-stu-id="68094-108">Retention duration of retention Policy.</span></span></param>
        <summary>
            <span data-ttu-id="68094-109">MonthlyRetentionSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="68094-109">Initializes a new instance of the MonthlyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration RetentionDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration RetentionDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDuration As RetentionDuration" />
      <MemberSignature Language="F#" Value="member this.RetentionDuration : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68094-110">取得または保持ポリシーの保持期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="68094-110">Gets or sets retention duration of retention Policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleDaily">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat RetentionScheduleDaily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat RetentionScheduleDaily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleDaily As DailyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleDaily : Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionScheduleDaily")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68094-111">取得またはの毎月の保持ポリシーの毎日の保存形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="68094-111">Gets or sets daily retention format for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleFormatType">
      <MemberSignature Language="C#" Value="public string RetentionScheduleFormatType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RetentionScheduleFormatType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionScheduleFormatType" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleFormatType As String" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleFormatType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionScheduleFormatType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionScheduleFormatType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68094-112">取得または保有期間の月単位の保持ポリシーのスケジュール形式の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="68094-112">Gets or sets retention schedule format type for monthly retention policy.</span></span> <span data-ttu-id="68094-113">使用可能な値が含まれます: '無効'、'毎日'、'毎週'</span><span class="sxs-lookup"><span data-stu-id="68094-113">Possible values include: 'Invalid', 'Daily', 'Weekly'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleWeekly">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat RetentionScheduleWeekly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat RetentionScheduleWeekly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleWeekly As WeeklyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleWeekly : Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionScheduleWeekly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68094-114">取得またはの毎月の保持ポリシーの毎週の保存形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="68094-114">Gets or sets weekly retention format for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTimes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; RetentionTimes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; RetentionTimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionTimes" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTimes As IList(Of Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="member this.RetentionTimes : System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthlyRetentionSchedule.RetentionTimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTimes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.DateTime&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68094-115">取得または保持ポリシーの保存期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="68094-115">Gets or sets retention times of retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>