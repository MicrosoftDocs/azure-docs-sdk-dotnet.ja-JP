<Type Name="TaskStatusInfo" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo">
  <TypeSignature Language="C#" Value="public class TaskStatusInfo : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskStatusInfo extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskStatusInfo&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type TaskStatusInfo = class&#xA;    inherit AzureOperationResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="aa3e5-101">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="aa3e5-101">Info about the async task</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskStatusInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa3e5-102">TaskStatusInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="aa3e5-102">Initializes a new instance of the TaskStatusInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsyncTaskAggregatedResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskAggregatedResult AsyncTaskAggregatedResult { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskAggregatedResult AsyncTaskAggregatedResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.AsyncTaskAggregatedResult" />
      <MemberSignature Language="VB.NET" Value="Public Property AsyncTaskAggregatedResult As AsyncTaskAggregatedResult" />
      <MemberSignature Language="F#" Value="member this.AsyncTaskAggregatedResult : Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskAggregatedResult with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.AsyncTaskAggregatedResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskAggregatedResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa3e5-103">必須。</span><span class="sxs-lookup"><span data-stu-id="aa3e5-103">Required.</span></span> <span data-ttu-id="aa3e5-104">タスクの結果</span><span class="sxs-lookup"><span data-stu-id="aa3e5-104">The result of the task</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.ErrorDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.ErrorDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ErrorDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.WindowsAzure.Management.StorSimple.Models.ErrorDetails with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.ErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa3e5-105">必須。</span><span class="sxs-lookup"><span data-stu-id="aa3e5-105">Required.</span></span> <span data-ttu-id="aa3e5-106">タスクのエラーのエラーの詳細</span><span class="sxs-lookup"><span data-stu-id="aa3e5-106">Error details for task's failures</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskResult Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskResult Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As AsyncTaskResult" />
      <MemberSignature Language="F#" Value="member this.Result : Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskResult with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa3e5-107">必須。</span><span class="sxs-lookup"><span data-stu-id="aa3e5-107">Required.</span></span> <span data-ttu-id="aa3e5-108">タスクの結果</span><span class="sxs-lookup"><span data-stu-id="aa3e5-108">Task's result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As AsyncTaskStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.AsyncTaskStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa3e5-109">必須。</span><span class="sxs-lookup"><span data-stu-id="aa3e5-109">Required.</span></span> <span data-ttu-id="aa3e5-110">タスクのステータス</span><span class="sxs-lookup"><span data-stu-id="aa3e5-110">Task's status</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.TaskId" />
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
            <span data-ttu-id="aa3e5-111">必須。</span><span class="sxs-lookup"><span data-stu-id="aa3e5-111">Required.</span></span> <span data-ttu-id="aa3e5-112">タスクの id</span><span class="sxs-lookup"><span data-stu-id="aa3e5-112">Task's id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSteps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStep&gt; TaskSteps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStep&gt; TaskSteps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.TaskSteps" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSteps As IList(Of TaskStep)" />
      <MemberSignature Language="F#" Value="member this.TaskSteps : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStep&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo.TaskSteps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStep&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa3e5-113">必須。</span><span class="sxs-lookup"><span data-stu-id="aa3e5-113">Required.</span></span> <span data-ttu-id="aa3e5-114">各ステップの状態で、タスクの一部である手順の一覧</span><span class="sxs-lookup"><span data-stu-id="aa3e5-114">List of steps which are part of the task, with each step's status</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>