<Type Name="YearlyRetentionSchedule" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule">
  <TypeSignature Language="C#" Value="public class YearlyRetentionSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit YearlyRetentionSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class YearlyRetentionSchedule" />
  <TypeSignature Language="F#" Value="type YearlyRetentionSchedule = class" />
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
            <span data-ttu-id="a5fe6-101">年の保有期間のスケジュール。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-101">Yearly retention schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public YearlyRetentionSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5fe6-102">YearlyRetentionSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-102">Initializes a new instance of the YearlyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public YearlyRetentionSchedule (string retentionScheduleFormatType = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt; monthsOfYear = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat retentionScheduleDaily = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat retentionScheduleWeekly = null, System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; retentionTimes = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration retentionDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string retentionScheduleFormatType, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt; monthsOfYear, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat retentionScheduleDaily, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat retentionScheduleWeekly, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; retentionTimes, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration retentionDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.#ctor(System.String,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear}},Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat,Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat,System.Collections.Generic.IList{System.Nullable{System.DateTime}},Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule : string * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat * Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat * System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule (retentionScheduleFormatType, monthsOfYear, retentionScheduleDaily, retentionScheduleWeekly, retentionTimes, retentionDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retentionScheduleFormatType" Type="System.String" />
        <Parameter Name="monthsOfYear" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt;" />
        <Parameter Name="retentionScheduleDaily" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat" />
        <Parameter Name="retentionScheduleWeekly" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat" />
        <Parameter Name="retentionTimes" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.DateTime&gt;&gt;" />
        <Parameter Name="retentionDuration" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration" />
      </Parameters>
      <Docs>
        <param name="retentionScheduleFormatType"><span data-ttu-id="a5fe6-103">年の保有ポリシーの保有期間のスケジュール形式です。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-103">Retention schedule format for yearly retention policy.</span></span> <span data-ttu-id="a5fe6-104">使用可能な値が含まれます: '無効'、'毎日'、'毎週'</span><span class="sxs-lookup"><span data-stu-id="a5fe6-104">Possible values include: 'Invalid', 'Daily', 'Weekly'</span></span></param>
        <param name="monthsOfYear"><span data-ttu-id="a5fe6-105">年の保有ポリシーの年の月の一覧です。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-105">List of months of year of yearly retention policy.</span></span></param>
        <param name="retentionScheduleDaily"><span data-ttu-id="a5fe6-106">年の保有ポリシーの毎日の保有期間形式。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-106">Daily retention format for yearly retention policy.</span></span></param>
        <param name="retentionScheduleWeekly"><span data-ttu-id="a5fe6-107">年の保有期間ポリシーの毎週の保有期間形式。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-107">Weekly retention format for yearly retention policy.</span></span></param>
        <param name="retentionTimes"><span data-ttu-id="a5fe6-108">保有ポリシーの保存期間。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-108">Retention times of retention policy.</span></span></param>
        <param name="retentionDuration"><span data-ttu-id="a5fe6-109">保有ポリシーの保有期間です。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-109">Retention duration of retention Policy.</span></span></param>
        <summary>
            <span data-ttu-id="a5fe6-110">YearlyRetentionSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-110">Initializes a new instance of the YearlyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonthsOfYear">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt; MonthsOfYear { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt; MonthsOfYear" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.MonthsOfYear" />
      <MemberSignature Language="VB.NET" Value="Public Property MonthsOfYear As IList(Of Nullable(Of MonthOfYear))" />
      <MemberSignature Language="F#" Value="member this.MonthsOfYear : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.MonthsOfYear" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="monthsOfYear")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MonthOfYear&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5fe6-111">取得または年単位の保有ポリシーの年の月の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-111">Gets or sets list of months of year of yearly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration RetentionDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration RetentionDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDuration As RetentionDuration" />
      <MemberSignature Language="F#" Value="member this.RetentionDuration : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionDuration" />
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
            <span data-ttu-id="a5fe6-112">取得または保持ポリシーの保持期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-112">Gets or sets retention duration of retention Policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleDaily">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat RetentionScheduleDaily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat RetentionScheduleDaily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleDaily As DailyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleDaily : Microsoft.Azure.Management.RecoveryServices.Backup.Models.DailyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionScheduleDaily" />
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
            <span data-ttu-id="a5fe6-113">取得または年単位の保有ポリシーの毎日の保存形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-113">Gets or sets daily retention format for yearly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleFormatType">
      <MemberSignature Language="C#" Value="public string RetentionScheduleFormatType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RetentionScheduleFormatType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionScheduleFormatType" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleFormatType As String" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleFormatType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionScheduleFormatType" />
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
            <span data-ttu-id="a5fe6-114">取得または年単位の保有ポリシーの保有期間のスケジュールの書式を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-114">Gets or sets retention schedule format for yearly retention policy.</span></span>
            <span data-ttu-id="a5fe6-115">使用可能な値が含まれます: '無効'、'毎日'、'毎週'</span><span class="sxs-lookup"><span data-stu-id="a5fe6-115">Possible values include: 'Invalid', 'Daily', 'Weekly'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleWeekly">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat RetentionScheduleWeekly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat RetentionScheduleWeekly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleWeekly As WeeklyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleWeekly : Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionScheduleWeekly" />
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
            <span data-ttu-id="a5fe6-116">取得または年単位の保有ポリシーの毎週の保存形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-116">Gets or sets weekly retention format for yearly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTimes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; RetentionTimes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; RetentionTimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionTimes" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTimes As IList(Of Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="member this.RetentionTimes : System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.YearlyRetentionSchedule.RetentionTimes" />
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
            <span data-ttu-id="a5fe6-117">取得または保持ポリシーの保存期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5fe6-117">Gets or sets retention times of retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>