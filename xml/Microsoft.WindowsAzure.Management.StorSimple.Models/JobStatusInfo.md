<Type Name="JobStatusInfo" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo">
  <TypeSignature Language="C#" Value="public class JobStatusInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStatusInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStatusInfo" />
  <TypeSignature Language="F#" Value="type JobStatusInfo = class" />
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
            <span data-ttu-id="af0fc-101">ジョブの状態情報</span><span class="sxs-lookup"><span data-stu-id="af0fc-101">Job status information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatusInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af0fc-102">JobStatusInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="af0fc-102">Initializes a new instance of the JobStatusInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.CisApiError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.CisApiError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As CisApiError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.WindowsAzure.Management.StorSimple.Models.CisApiError with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.CisApiError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af0fc-103">必須。</span><span class="sxs-lookup"><span data-stu-id="af0fc-103">Required.</span></span> <span data-ttu-id="af0fc-104">エラーの詳細</span><span class="sxs-lookup"><span data-stu-id="af0fc-104">Error details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.JobId" />
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
            <span data-ttu-id="af0fc-105">必須。</span><span class="sxs-lookup"><span data-stu-id="af0fc-105">Required.</span></span> <span data-ttu-id="af0fc-106">ジョブの一意の Id</span><span class="sxs-lookup"><span data-stu-id="af0fc-106">Unique Id of Job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSteps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobStep&gt; JobSteps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobStep&gt; JobSteps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.JobSteps" />
      <MemberSignature Language="VB.NET" Value="Public Property JobSteps As IList(Of JobStep)" />
      <MemberSignature Language="F#" Value="member this.JobSteps : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobStep&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.JobSteps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobStep&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af0fc-107">必須。</span><span class="sxs-lookup"><span data-stu-id="af0fc-107">Required.</span></span> <span data-ttu-id="af0fc-108">ジョブ ステップ</span><span class="sxs-lookup"><span data-stu-id="af0fc-108">Job Steps</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.JobResult Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.JobResult Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As JobResult" />
      <MemberSignature Language="F#" Value="member this.Result : Microsoft.WindowsAzure.Management.StorSimple.Models.JobResult with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af0fc-109">必須。</span><span class="sxs-lookup"><span data-stu-id="af0fc-109">Required.</span></span> <span data-ttu-id="af0fc-110">結果</span><span class="sxs-lookup"><span data-stu-id="af0fc-110">Result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As JobStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af0fc-111">必須。</span><span class="sxs-lookup"><span data-stu-id="af0fc-111">Required.</span></span> <span data-ttu-id="af0fc-112">ジョブの状態</span><span class="sxs-lookup"><span data-stu-id="af0fc-112">Job status</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResult TaskResult { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResult TaskResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.TaskResult" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskResult As TaskResult" />
      <MemberSignature Language="F#" Value="member this.TaskResult : Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResult with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.JobStatusInfo.TaskResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af0fc-113">必須。</span><span class="sxs-lookup"><span data-stu-id="af0fc-113">Required.</span></span> <span data-ttu-id="af0fc-114">タスクの結果</span><span class="sxs-lookup"><span data-stu-id="af0fc-114">Task Result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>