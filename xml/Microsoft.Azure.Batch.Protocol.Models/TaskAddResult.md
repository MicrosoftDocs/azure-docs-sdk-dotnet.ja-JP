<Type Name="TaskAddResult" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult">
  <TypeSignature Language="C#" Value="public class TaskAddResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskAddResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskAddResult" />
  <TypeSignature Language="F#" Value="type TaskAddResult = class" />
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
            <span data-ttu-id="dc588-101">追加のタスクのコレクションの操作の一部として追加された 1 つのタスクの結果。</span><span class="sxs-lookup"><span data-stu-id="dc588-101">Result for a single task added as part of an add task collection operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc588-102">TaskAddResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc588-102">Initializes a new instance of the TaskAddResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddResult (Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus status, string taskId, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, string location = null, Microsoft.Azure.Batch.Protocol.Models.BatchError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus status, string taskId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, string location, class Microsoft.Azure.Batch.Protocol.Models.BatchError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.#ctor(Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus,System.String,System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.BatchError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (status As TaskAddStatus, taskId As String, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null, Optional location As String = null, Optional error As BatchError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskAddResult : Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus * string * string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.BatchError -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddResult" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskAddResult (status, taskId, eTag, lastModified, location, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Batch.Protocol.Models.BatchError" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="dc588-103">追加のタスクの要求の状態。</span><span class="sxs-lookup"><span data-stu-id="dc588-103">The status of the add task request.</span></span></param>
        <param name="taskId"><span data-ttu-id="dc588-104">結果の基になるタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="dc588-104">The ID of the task for which this is the result.</span></span></param>
        <param name="eTag"><span data-ttu-id="dc588-105">タスクが正常に追加されている場合は、タスクの ETag です。</span><span class="sxs-lookup"><span data-stu-id="dc588-105">The ETag of the task, if the task was successfully added.</span></span></param>
        <param name="lastModified"><span data-ttu-id="dc588-106">最終は、タスクの時間を更新します。</span><span class="sxs-lookup"><span data-stu-id="dc588-106">The last modified time of the task.</span></span></param>
        <param name="location"><span data-ttu-id="dc588-107">場合は、タスク、タスクが正常に追加の URL です。</span><span class="sxs-lookup"><span data-stu-id="dc588-107">The URL of the task, if the task was successfully added.</span></span></param>
        <param name="error"><span data-ttu-id="dc588-108">タスクを追加しようとしているときに発生したエラー。</span><span class="sxs-lookup"><span data-stu-id="dc588-108">The error encountered while attempting to add the task.</span></span></param>
        <summary>
            <span data-ttu-id="dc588-109">TaskAddResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc588-109">Initializes a new instance of the TaskAddResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.BatchError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.BatchError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As BatchError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Batch.Protocol.Models.BatchError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.BatchError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc588-110">取得またはタスクを追加しようとしているときに発生したエラーを設定します。</span><span class="sxs-lookup"><span data-stu-id="dc588-110">Gets or sets the error encountered while attempting to add the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc588-111">取得またはタスクが正常に追加された場合、タスクの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc588-111">Gets or sets the ETag of the task, if the task was successfully added.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="dc588-112">これを使用して、要求間で、タスクが変更されたかどうかを検出することができます。</span><span class="sxs-lookup"><span data-stu-id="dc588-112">You can use this to detect whether the task has changed between requests.</span></span> <span data-ttu-id="dc588-113">特には、更新タスク、変更が反映されるその他のユーザーが変更、ジョブ、その間場合にのみを指定する要求に ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="dc588-113">In particular, you can be pass the ETag with an Update Task request to specify that your changes should take effect only if nobody else has modified the job in the meantime.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc588-114">取得またはタスクの最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc588-114">Gets or sets the last modified time of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc588-115">取得またはタスクが正常に追加された場合、タスクの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc588-115">Gets or sets the URL of the task, if the task was successfully added.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As TaskAddStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc588-116">取得または追加のタスクの要求の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc588-116">Gets or sets the status of the add task request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="dc588-117">使用可能な値が含まれます: 'は success'、'clientError'、'serverError'</span><span class="sxs-lookup"><span data-stu-id="dc588-117">Possible values include: 'success', 'clientError', 'serverError'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc588-118">取得または結果の基になるタスクの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc588-118">Gets or sets the ID of the task for which this is the result.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddResult.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskAddResult.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc588-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="dc588-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dc588-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dc588-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>