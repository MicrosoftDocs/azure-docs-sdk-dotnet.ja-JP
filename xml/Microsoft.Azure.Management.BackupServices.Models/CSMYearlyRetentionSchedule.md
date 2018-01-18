<Type Name="CSMYearlyRetentionSchedule" FullName="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule">
  <TypeSignature Language="C#" Value="public class CSMYearlyRetentionSchedule : Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CSMYearlyRetentionSchedule extends Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class CSMYearlyRetentionSchedule&#xA;Inherits CSMRetentionScheduleBase" />
  <TypeSignature Language="F#" Value="type CSMYearlyRetentionSchedule = class&#xA;    inherit CSMRetentionScheduleBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BackupServices.Models.CSMRetentionScheduleBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9e978-101">CSMYearlyRetentionSchedule オブジェクトの定義。</span><span class="sxs-lookup"><span data-stu-id="9e978-101">The definition of a CSMYearlyRetentionSchedule object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMYearlyRetentionSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9e978-102">CSMYearlyRetentionSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9e978-102">Initializes a new instance of the CSMYearlyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonthsOfYear">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.Month&gt; MonthsOfYear { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Management.BackupServices.Models.Month&gt; MonthsOfYear" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.MonthsOfYear" />
      <MemberSignature Language="VB.NET" Value="Public Property MonthsOfYear As IList(Of Month)" />
      <MemberSignature Language="F#" Value="member this.MonthsOfYear : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.Month&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.MonthsOfYear" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BackupServices.Models.Month&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e978-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9e978-103">Optional.</span></span> <span data-ttu-id="9e978-104">年の保有ポリシーの年の月の一覧です。</span><span class="sxs-lookup"><span data-stu-id="9e978-104">List of months of year of yearly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleDaily">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat RetentionScheduleDaily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat RetentionScheduleDaily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleDaily As CSMDailyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleDaily : Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleDaily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMDailyRetentionFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e978-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9e978-105">Optional.</span></span> <span data-ttu-id="9e978-106">毎月の保持ポリシーの毎日の保存形式です。</span><span class="sxs-lookup"><span data-stu-id="9e978-106">Daily Retention Format for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat RetentionScheduleType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat RetentionScheduleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleType" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleType As RetentionScheduleFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleType : Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.RetentionScheduleFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e978-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9e978-107">Optional.</span></span> <span data-ttu-id="9e978-108">月単位の保有ポリシーの保存 ScheduleType です。</span><span class="sxs-lookup"><span data-stu-id="9e978-108">Retention ScheduleType for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionScheduleWeekly">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat RetentionScheduleWeekly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat RetentionScheduleWeekly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionScheduleWeekly As CSMWeeklyRetentionFormat" />
      <MemberSignature Language="F#" Value="member this.RetentionScheduleWeekly : Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMYearlyRetentionSchedule.RetentionScheduleWeekly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMWeeklyRetentionFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e978-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="9e978-109">Optional.</span></span> <span data-ttu-id="9e978-110">毎月の保持ポリシーの毎週の保存形式です。</span><span class="sxs-lookup"><span data-stu-id="9e978-110">Weekly Retention format for monthly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>