<Type Name="TaskInformation" FullName="Microsoft.Azure.Batch.TaskInformation">
  <TypeSignature Language="C#" Value="public class TaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskInformation" />
  <TypeSignature Language="F#" Value="type TaskInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9bcf9-101">コンピューティング ノードの作業情報のクラスです。</span><span class="sxs-lookup"><span data-stu-id="9bcf9-101">The compute node's task info class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskExecutionInformation ExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskExecutionInformation ExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskInformation.ExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionInformation As TaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInformation : Microsoft.Azure.Batch.TaskExecutionInformation" Usage="Microsoft.Azure.Batch.TaskInformation.ExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bcf9-102">タスクの実行情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9bcf9-102">Gets the execution information for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskInformation.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string" Usage="Microsoft.Azure.Batch.TaskInformation.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bcf9-103">ジョブ id を取得します。</span><span class="sxs-lookup"><span data-stu-id="9bcf9-103">Gets the job id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubtaskId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SubtaskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SubtaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskInformation.SubtaskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubtaskId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SubtaskId : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.TaskInformation.SubtaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bcf9-104">サブタスク id を取得します。</span><span class="sxs-lookup"><span data-stu-id="9bcf9-104">Gets the subtask id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskInformation.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string" Usage="Microsoft.Azure.Batch.TaskInformation.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bcf9-105">タスク id を取得します。</span><span class="sxs-lookup"><span data-stu-id="9bcf9-105">Gets the task id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.TaskState TaskState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.TaskState TaskState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskInformation.TaskState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskState As TaskState" />
      <MemberSignature Language="F#" Value="member this.TaskState : Microsoft.Azure.Batch.Common.TaskState" Usage="Microsoft.Azure.Batch.TaskInformation.TaskState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bcf9-106">タスクの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="9bcf9-106">Gets the task state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskUrl">
      <MemberSignature Language="C#" Value="public string TaskUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskInformation.TaskUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskUrl : string" Usage="Microsoft.Azure.Batch.TaskInformation.TaskUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bcf9-107">タスクの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="9bcf9-107">Gets the task URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>