<Type Name="DpmJobTaskDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails">
  <TypeSignature Language="C#" Value="public class DpmJobTaskDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmJobTaskDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmJobTaskDetails" />
  <TypeSignature Language="F#" Value="type DpmJobTaskDetails = class" />
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
            <span data-ttu-id="23155-101">DPM ワークロードに固有のジョブのタスクの詳細。</span><span class="sxs-lookup"><span data-stu-id="23155-101">DPM workload-specific job task details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmJobTaskDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23155-102">DpmJobTaskDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23155-102">Initializes a new instance of the DpmJobTaskDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmJobTaskDetails (string taskId = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;TimeSpan&gt; duration = null, string status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string taskId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, string status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.TimeSpan},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional taskId As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional duration As Nullable(Of TimeSpan) = null, Optional status As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails : string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;TimeSpan&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails (taskId, startTime, endTime, duration, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="status" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="taskId"><span data-ttu-id="23155-103">タスクの表示名。</span><span class="sxs-lookup"><span data-stu-id="23155-103">The task display name.</span></span></param>
        <param name="startTime"><span data-ttu-id="23155-104">開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="23155-104">The start time.</span></span></param>
        <param name="endTime"><span data-ttu-id="23155-105">終了時刻。</span><span class="sxs-lookup"><span data-stu-id="23155-105">The end time.</span></span></param>
        <param name="duration"><span data-ttu-id="23155-106">タスクの経過時間です。</span><span class="sxs-lookup"><span data-stu-id="23155-106">Time elapsed for task.</span></span></param>
        <param name="status"><span data-ttu-id="23155-107">ステータス。</span><span class="sxs-lookup"><span data-stu-id="23155-107">The status.</span></span></param>
        <summary>
            <span data-ttu-id="23155-108">DpmJobTaskDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23155-108">Initializes a new instance of the DpmJobTaskDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Duration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.Duration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="duration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23155-109">取得または設定タスクの経過時間。</span><span class="sxs-lookup"><span data-stu-id="23155-109">Gets or sets time elapsed for task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23155-110">取得または終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="23155-110">Gets or sets the end time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="23155-111">取得または開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="23155-111">Gets or sets the start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23155-112">取得または状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="23155-112">Gets or sets the status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobTaskDetails.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="23155-113">取得またはタスクの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="23155-113">Gets or sets the task display name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>