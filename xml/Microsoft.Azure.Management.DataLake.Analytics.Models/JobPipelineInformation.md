<Type Name="JobPipelineInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation">
  <TypeSignature Language="C#" Value="public class JobPipelineInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPipelineInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPipelineInformation" />
  <TypeSignature Language="F#" Value="type JobPipelineInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="358f3-101">ジョブ パイプラインについては、パイプラインでのジョブの関係とこれらのジョブを実行する表示します。</span><span class="sxs-lookup"><span data-stu-id="358f3-101">Job Pipeline Information, showing the relationship of jobs and recurrences of those jobs in a pipeline.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPipelineInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="358f3-102">JobPipelineInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="358f3-102">Initializes a new instance of the JobPipelineInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPipelineInformation (Nullable&lt;Guid&gt; pipelineId = null, string pipelineName = null, string pipelineUri = null, Nullable&lt;int&gt; numJobsFailed = null, Nullable&lt;int&gt; numJobsCanceled = null, Nullable&lt;int&gt; numJobsSucceeded = null, Nullable&lt;double&gt; auHoursFailed = null, Nullable&lt;double&gt; auHoursCanceled = null, Nullable&lt;double&gt; auHoursSucceeded = null, Nullable&lt;DateTimeOffset&gt; lastSubmitTime = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; runs = null, System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt; recurrences = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; pipelineId, string pipelineName, string pipelineUri, valuetype System.Nullable`1&lt;int32&gt; numJobsFailed, valuetype System.Nullable`1&lt;int32&gt; numJobsCanceled, valuetype System.Nullable`1&lt;int32&gt; numJobsSucceeded, valuetype System.Nullable`1&lt;float64&gt; auHoursFailed, valuetype System.Nullable`1&lt;float64&gt; auHoursCanceled, valuetype System.Nullable`1&lt;float64&gt; auHoursSucceeded, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; lastSubmitTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; runs, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.Guid&gt;&gt; recurrences) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.#ctor(System.Nullable{System.Guid},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTimeOffset},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation},System.Collections.Generic.IList{System.Nullable{System.Guid}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional pipelineId As Nullable(Of Guid) = null, Optional pipelineName As String = null, Optional pipelineUri As String = null, Optional numJobsFailed As Nullable(Of Integer) = null, Optional numJobsCanceled As Nullable(Of Integer) = null, Optional numJobsSucceeded As Nullable(Of Integer) = null, Optional auHoursFailed As Nullable(Of Double) = null, Optional auHoursCanceled As Nullable(Of Double) = null, Optional auHoursSucceeded As Nullable(Of Double) = null, Optional lastSubmitTime As Nullable(Of DateTimeOffset) = null, Optional runs As IList(Of JobPipelineRunInformation) = null, Optional recurrences As IList(Of Nullable(Of Guid)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation : Nullable&lt;Guid&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTimeOffset&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; * System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation (pipelineId, pipelineName, pipelineUri, numJobsFailed, numJobsCanceled, numJobsSucceeded, auHoursFailed, auHoursCanceled, auHoursSucceeded, lastSubmitTime, runs, recurrences)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pipelineId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipelineUri" Type="System.String" />
        <Parameter Name="numJobsFailed" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsCanceled" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="auHoursFailed" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursCanceled" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursSucceeded" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="lastSubmitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="runs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt;" />
        <Parameter Name="recurrences" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Guid&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="pipelineId"><span data-ttu-id="358f3-103">ジョブの関係パイプライン識別子 (GUID) です。</span><span class="sxs-lookup"><span data-stu-id="358f3-103">the job relationship pipeline identifier (a GUID).</span></span></param>
        <param name="pipelineName"><span data-ttu-id="358f3-104">フレンドリなパイプラインの名前、ジョブの関係、一意である必要はありません。</span><span class="sxs-lookup"><span data-stu-id="358f3-104">the friendly name of the job relationship pipeline, which does not need to be unique.</span></span></param>
        <param name="pipelineUri"><span data-ttu-id="358f3-105">このパイプラインには、元のサービスにパイプライン、uri、一意のリンク</span><span class="sxs-lookup"><span data-stu-id="358f3-105">the pipeline uri, unique, links to the originating service for this pipeline.</span></span></param>
        <param name="numJobsFailed"><span data-ttu-id="358f3-106">このパイプライン内で失敗したジョブの数。</span><span class="sxs-lookup"><span data-stu-id="358f3-106">the number of jobs in this pipeline that have failed.</span></span></param>
        <param name="numJobsCanceled"><span data-ttu-id="358f3-107">このパイプラインで取り消されたジョブの数。</span><span class="sxs-lookup"><span data-stu-id="358f3-107">the number of jobs in this pipeline that have been canceled.</span></span></param>
        <param name="numJobsSucceeded"><span data-ttu-id="358f3-108">このパイプラインに成功したジョブの数。</span><span class="sxs-lookup"><span data-stu-id="358f3-108">the number of jobs in this pipeline that have succeeded.</span></span></param>
        <param name="auHoursFailed"><span data-ttu-id="358f3-109">失敗したジョブの結果のジョブ実行時間の数。</span><span class="sxs-lookup"><span data-stu-id="358f3-109">the number of job execution hours that resulted in failed jobs.</span></span></param>
        <param name="auHoursCanceled"><span data-ttu-id="358f3-110">発生したジョブ実行時間の数には、ジョブが取り消されました。</span><span class="sxs-lookup"><span data-stu-id="358f3-110">the number of job execution hours that resulted in canceled jobs.</span></span></param>
        <param name="auHoursSucceeded"><span data-ttu-id="358f3-111">成功したジョブの結果のジョブ実行時間の数。</span><span class="sxs-lookup"><span data-stu-id="358f3-111">the number of job execution hours that resulted in successful jobs.</span></span></param>
        <param name="lastSubmitTime"><span data-ttu-id="358f3-112">このパイプライン内のジョブが送信された最後の時間。</span><span class="sxs-lookup"><span data-stu-id="358f3-112">the last time a job in this pipeline was submitted.</span></span></param>
        <param name="runs"><span data-ttu-id="358f3-113">このパイプラインの実行の各を表す繰り返しの識別子のリスト。</span><span class="sxs-lookup"><span data-stu-id="358f3-113">the list of recurrence identifiers representing each run of this pipeline.</span></span></param>
        <param name="recurrences"><span data-ttu-id="358f3-114">このパイプラインの実行の各を表す繰り返しの識別子のリスト。</span><span class="sxs-lookup"><span data-stu-id="358f3-114">the list of recurrence identifiers representing each run of this pipeline.</span></span></param>
        <summary>
            <span data-ttu-id="358f3-115">JobPipelineInformation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="358f3-115">Initializes a new instance of the JobPipelineInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursCanceled As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursCanceled : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-116">取り消されたジョブの結果のジョブ実行時間の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-116">Gets the number of job execution hours that resulted in canceled jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursFailed As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursFailed : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-117">失敗したジョブの結果のジョブ実行時間の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-117">Gets the number of job execution hours that resulted in failed jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursSucceeded As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursSucceeded : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.AuHoursSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-118">成功したジョブの結果のジョブ実行時間の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-118">Gets the number of job execution hours that resulted in successful jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSubmitTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastSubmitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastSubmitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.LastSubmitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSubmitTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastSubmitTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.LastSubmitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastSubmitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-119">このパイプライン内のジョブが送信された最後の時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-119">Gets the last time a job in this pipeline was submitted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsCanceled As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsCanceled : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-120">取り消されたこのパイプラインでは、ジョブの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-120">Gets the number of jobs in this pipeline that have been canceled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsFailed As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsFailed : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-121">このパイプラインで失敗したジョブの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-121">Gets the number of jobs in this pipeline that have failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsSucceeded : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.NumJobsSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-122">成功したこのパイプラインでは、ジョブの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-122">Gets the number of jobs in this pipeline that have succeeded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PipelineId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PipelineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PipelineId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-123">ジョブの関係パイプライン識別子 (GUID) を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-123">Gets the job relationship pipeline identifier (a GUID).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineName">
      <MemberSignature Language="C#" Value="public string PipelineName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineName As String" />
      <MemberSignature Language="F#" Value="member this.PipelineName : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-124">一意である必要はありません、ジョブの関係パイプラインのフレンドリ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-124">Gets the friendly name of the job relationship pipeline, which does not need to be unique.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineUri">
      <MemberSignature Language="C#" Value="public string PipelineUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineUri As String" />
      <MemberSignature Language="F#" Value="member this.PipelineUri : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.PipelineUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-125">パイプライン uri、一意で、このパイプラインには、元のサービスへのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-125">Gets the pipeline uri, unique, links to the originating service for this pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt; Recurrences { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.Guid&gt;&gt; Recurrences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Recurrences" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Recurrences As IList(Of Nullable(Of Guid))" />
      <MemberSignature Language="F#" Value="member this.Recurrences : System.Collections.Generic.IList&lt;Nullable&lt;Guid&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Recurrences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Guid&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-126">このパイプラインの各実行を表す繰り返しの識別子の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-126">Gets the list of recurrence identifiers representing each run of this pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; Runs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt; Runs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Runs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Runs As IList(Of JobPipelineRunInformation)" />
      <MemberSignature Language="F#" Value="member this.Runs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Runs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineRunInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="358f3-127">このパイプラインの各実行を表す繰り返しの識別子の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="358f3-127">Gets the list of recurrence identifiers representing each run of this pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPipelineInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="358f3-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="358f3-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="358f3-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="358f3-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>