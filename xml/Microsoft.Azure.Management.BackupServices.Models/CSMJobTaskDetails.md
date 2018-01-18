<Type Name="CSMJobTaskDetails" FullName="Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails">
  <TypeSignature Language="C#" Value="public class CSMJobTaskDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CSMJobTaskDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class CSMJobTaskDetails" />
  <TypeSignature Language="F#" Value="type CSMJobTaskDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7fa5a-101">ジョブのサブタスクを記述するクラス</span><span class="sxs-lookup"><span data-stu-id="7fa5a-101">Class that describes subtasks of a job</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMJobTaskDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7fa5a-102">CSMJobTaskDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7fa5a-102">Initializes a new instance of the CSMJobTaskDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public TimeSpan Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Duration : TimeSpan with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.Duration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fa5a-103">必須。</span><span class="sxs-lookup"><span data-stu-id="7fa5a-103">Required.</span></span> <span data-ttu-id="7fa5a-104">期間を指定するフィールド</span><span class="sxs-lookup"><span data-stu-id="7fa5a-104">Field to indicate the duration</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fa5a-105">必須。</span><span class="sxs-lookup"><span data-stu-id="7fa5a-105">Required.</span></span> <span data-ttu-id="7fa5a-106">タスクの終了時刻を示すためにフィールド</span><span class="sxs-lookup"><span data-stu-id="7fa5a-106">Field to indicate endtime of the task</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProgressPercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ProgressPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ProgressPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.ProgressPercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property ProgressPercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ProgressPercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.ProgressPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fa5a-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7fa5a-107">Optional.</span></span> <span data-ttu-id="7fa5a-108">各サブタスクの進行状況の割合を示すためにフィールド</span><span class="sxs-lookup"><span data-stu-id="7fa5a-108">Field to indicate progress percentage of each subtask</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fa5a-109">必須。</span><span class="sxs-lookup"><span data-stu-id="7fa5a-109">Required.</span></span> <span data-ttu-id="7fa5a-110">タスクの開始時刻を示すためにフィールド</span><span class="sxs-lookup"><span data-stu-id="7fa5a-110">Field to indicate starttime of the task</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fa5a-111">必須。</span><span class="sxs-lookup"><span data-stu-id="7fa5a-111">Required.</span></span> <span data-ttu-id="7fa5a-112">状態を表すフィールド</span><span class="sxs-lookup"><span data-stu-id="7fa5a-112">Field to indicate status</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMJobTaskDetails.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fa5a-113">必須。</span><span class="sxs-lookup"><span data-stu-id="7fa5a-113">Required.</span></span> <span data-ttu-id="7fa5a-114">サブタスクの名前</span><span class="sxs-lookup"><span data-stu-id="7fa5a-114">Name of the subtask</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>