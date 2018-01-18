<Type Name="BackupScheduleBase" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase">
  <TypeSignature Language="C#" Value="public class BackupScheduleBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupScheduleBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupScheduleBase" />
  <TypeSignature Language="F#" Value="type BackupScheduleBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="055f9-101">このクラスは、バックアップ スケジュール オブジェクトの id を持たないのベース オブジェクトを表します。</span><span class="sxs-lookup"><span data-stu-id="055f9-101">This class represents the base object for a backup schedule object - without id.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupScheduleBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="055f9-102">BackupScheduleBase クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="055f9-102">Initializes a new instance of the BackupScheduleBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As BackupType" />
      <MemberSignature Language="F#" Value="member this.BackupType : Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.BackupType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="055f9-103">必須。</span><span class="sxs-lookup"><span data-stu-id="055f9-103">Required.</span></span> <span data-ttu-id="055f9-104">バックアップの種類。</span><span class="sxs-lookup"><span data-stu-id="055f9-104">The type of the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrence">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence Recurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence Recurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Recurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property Recurrence As ScheduleRecurrence" />
      <MemberSignature Language="F#" Value="member this.Recurrence : Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Recurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="055f9-105">必須。</span><span class="sxs-lookup"><span data-stu-id="055f9-105">Required.</span></span> <span data-ttu-id="055f9-106">このスケジュールの定期的なアイテム。</span><span class="sxs-lookup"><span data-stu-id="055f9-106">The recurrence of this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionCount">
      <MemberSignature Language="C#" Value="public long RetentionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RetentionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.RetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.RetentionCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.RetentionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="055f9-107">必須。</span><span class="sxs-lookup"><span data-stu-id="055f9-107">Required.</span></span> <span data-ttu-id="055f9-108">このスケジュールのバックアップの保有期間の数。</span><span class="sxs-lookup"><span data-stu-id="055f9-108">Retention count for backups of this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public string StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As String" />
      <MemberSignature Language="F#" Value="member this.StartTime : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="055f9-109">必須。</span><span class="sxs-lookup"><span data-stu-id="055f9-109">Required.</span></span> <span data-ttu-id="055f9-110">このスケジュールの開始時刻。</span><span class="sxs-lookup"><span data-stu-id="055f9-110">The StartTime for this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As ScheduleStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="055f9-111">必須。</span><span class="sxs-lookup"><span data-stu-id="055f9-111">Required.</span></span> <span data-ttu-id="055f9-112">スケジュールの状態</span><span class="sxs-lookup"><span data-stu-id="055f9-112">The status of the schedule</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>